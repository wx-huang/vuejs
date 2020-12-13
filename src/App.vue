<template>
  <!-- 3 使用 -->
  <div id="app">
    <router-view/>
    <main-tab-bar/>
  </div>
</template>                 

<script>
  // 1 导入
  import MainTabBar from './components/content/mainTabbar/MainTabBar'

  export default {
    name: 'App',
    // 2 注册
    components: {
      MainTabBar
    }

  }
</script>

<style>
  @import "assets/css/base.css";


</style>
