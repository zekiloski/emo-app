<!--Logica-->
<script setup>
const name = 'APP EMO';
const stylecolor = "color: greenyellow";
const arraycolores = ["blue","red","peru"];
const activo = false;
</script>

<!--Estructura render-->
<template>
  <h1>Bienvenidos a la {{ name.toLocaleUpperCase() }}</h1>
  <p></p>

  <h2 :style= "`color:${arraycolores[2]} `" >Fabrica de Implementos Agricolas</h2>
  <h2>
    {{ activo ? "Estoy activo" : "Estoy inactivo" }}
  </h2>
</template>


<!--Estilos-->
<style>
  h1 {
    color: green;
  }
</style>