<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Weelcome to Your Vue.js App"/>
    <IndexPage msg="asda"></IndexPage>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import IndexPage from '@/components/IndexPage.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
    IndexPage
  }
}
</script>
