<template>
  <div id="app">
    <h1>\{{ msg }}</h1>
  </div>
</template>

<script type="text/babel">
module.exports = {
  data () {
    return {
      msg: `Hello Vue ${1 + 1}.0!`
    }
  }
}
</script>

<style>
body {
  font-family: Helvetica, sans-serif;
}
</style>
