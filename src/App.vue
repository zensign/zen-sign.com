<template>
  <div id="app">
    
    <site-header></site-header>

    <landing></landing>

    <div class="chevron"></div>

    <div class="content">
      <a name="about"></a>
      <about></about>
      <a name="experience"></a>
      <experience></experience>
      <a name="education"></a>
      <education></education>
      <a name="contact"></a>
      <contact></contact>
    </div>

    <site-footer></site-footer>

  </div>
</template>

<script>
import SiteHeader from './components/SiteHeader.vue'
import SiteFooter from './components/SiteFooter.vue'
import Landing from './components/Landing.vue'
import About from './components/About.vue'
import Experience from './components/Experience.vue'
import Education from './components/Education.vue'
import Contact from './components/Contact.vue'

export default {
  name: 'app',
  components: {
    'site-header' : SiteHeader,
    'site-footer' : SiteFooter,
    'landing' : Landing,
    'about' : About,
    'experience' : Experience,
    'education' : Education,
    'contact' : Contact
  }
}
</script>

<style lang="scss">
  @import "./assets/styles/main.scss"
</style>
