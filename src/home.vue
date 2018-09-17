<template lang="html">

  <section class="home">
    <h1>home Component</h1>
    <navbar-component></navbar-component>
        <div class="container">
            <page-heading-component></page-heading-component>
            <staff-list-component></staff-list-component>
        </div>
  </section>

</template>

<script lang="js">

import PageHeadingComponent from './page-heading-component'
    import StaffListComponent from './staff-list-component.vue'
    import NavbarComponent from './navbar-component.vue'

  export default  {
    name: 'home',
    components: {NavbarComponent, PageHeadingComponent, StaffListComponent}, //Register other components

    props: [],
    mounted() {

    },
    data() {
      return {

      }
    },
    methods: {

    },
    computed: {

    }
}
</script>

<style scoped lang="scss">
  .home {

  }
</style>
