<template>
  <!--nuxt.js将/layout/default.vue作为所有页面的默认布局，通常布局包括：页头、内容区、页尾-->
  <div>
    <Header />
    <nuxt/>
    <Footer />
  </div>
</template>
<script>
  import Footer from '../components/Footer.vue'
  import Header from '../components/Header.vue'
  export default {
    components: {
      Header,
      Footer
    }
  }
</script>
<style>

</style>
