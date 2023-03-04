<template>
  <div>
    <div>{{ message }}</div>
    <div>{{ text }}</div>
    git config --global user.email "you@example.com"
    git config --global user.name "Your Name"
  </div>
</template>
<script>
export default {
  name: 'Home',
  data() {
    return {
      message: 'test',
      text: 'sumb'
    }
  }
}
</script>
