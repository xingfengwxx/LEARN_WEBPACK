<!--
 * @Author: 王星星
 * @Email: 1099420259@qq.com
 * @Date: 2022-09-22 10:48:01
 * @LastEditors: 王星星
 * @LastEditTime: 2022-09-22 10:52:37
 * @FilePath: \LEARN_WEBPACK\src\vue\App.vue
 * @Description: 
-->
<template>
  <h2>我是Vue渲染出来的</h2>
  <h2>{{title}}</h2>
  <hello-world></hello-world>
</template>

<script>
  import HelloWorld from './HelloWorld';

  export default {
    components: {
      HelloWorld
    },
    data() {
      return {
        title: "Hello World, wxx ",
        message: "hehehe"
      }
    },
    methods: {

    }
  }
</script>

<style scoped>
  h2 {
    color: red;
  }
</style>