<template>
  <v-app>
    <Toolbar></Toolbar>
    <v-content>
        <router-view></router-view>
    </v-content>
  </v-app>
</template>

<script>

import Toolbar from './components/Toolbar'

export default {
  name: 'App',
  components: {
    Toolbar
  },
  data () {
    return {

    }
  }
}
</script>
