<template>
  <div id="app">
    <my-header></my-header>
    <router-view></router-view>
    <my-footer v-show="$route.meta.show"></my-footer>
  </div>
</template>

<script>
import MyHeader from "./components/header";
import MyFooter from "./components/footer";
export default {
  name: "App",
  components: {
    MyHeader,
    MyFooter
  }
};
</script>

<style>
</style>
