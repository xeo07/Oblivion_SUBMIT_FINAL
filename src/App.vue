feature/nikita/product
<template>
    <div class="app">
    <SiteHeader />
    <ProductsPage />
    <SiteFooter />
    <HomePage />
    <ProjectsPage />
  </div>
</template>

<script setup>
import SiteHeader from './components/SiteHeader.vue';
import ProductsPage from './components/ProductPage.vue';
import SiteFooter from './components/SiteFooter.vue';
import HomePage from './pages/HomePage.vue';
import ProjectsPage from './pages/ProjectsPage.vue';
</script>
