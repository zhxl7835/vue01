<template>
  <div>
    <Navlist/>
    <h1>My first VueProject</h1>
  </div>
</template>

<script>
  import Navlist from "./Navlist"
  export default {
    name: "index",
    data(){
      return{

      }
    },
    components:{
      Navlist
    }
  }
</script>

<style scoped>

</style>
