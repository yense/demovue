<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="JUGANDO CON VUEJS"/>
    <div>
      {{name}}
    </div>
    <div>
      que lo que me gusta {{jovi}}
    </div>
    <div>
      <input type="text" v-model="cambio"> -->> {{cambio}}
    </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  data(){
    return {
      name:'yense david ventura',
      jovi:'programar',
      cambio:'',
    }
  },
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
