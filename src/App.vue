<template>
  
  <v-app>
    <SideBar></SideBar>
    <v-app-bar></v-app-bar>
    <v-main>
      <image-gallery>

      </image-gallery>
    </v-main>
  </v-app>
</template>

<script>
import SideBar from './components/SideBar.vue'
import ImageGallery from './components/ImageGallery.vue'

export default {
  name: 'App',

  components: {
    SideBar,
    ImageGallery
  },

  data: () => ({
    //
  }),
}
</script>
