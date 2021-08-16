<template>
  <div id="app">
    <router-view/>
    <FotterGuide v-show="$route.meta.showFooter"/>
  </div>
</template>

<script>
import FotterGuide from './components/FooterGuide/FooterGuide.vue'
export default {
  name: 'App',
  components:{
    FotterGuide
  }
}
</script>

<style lang="stylus" rel="stylesheet/stylus">
  .app
    width 100%
    height 100%
    background #f5f5f5
</style>