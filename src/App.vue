<template>
  <h1>{{count}}</h1>
  <HelloWorld />
  <div/>
</template>

<script>
  import HelloWorld from '~/components/HelloWorld'

  export default {
    components: {
      HelloWorld
    },
    data () {
      return {
        count : 0
      }
    }
  }
</script>

<style>
  h1 {
    font-size: 30px;
    color:aquamarine;
  }
</style>