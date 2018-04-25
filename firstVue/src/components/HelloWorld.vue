<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>中国</h2>
    <ul>
      <li>
        <a  href="https://vuejs.org" target="_blank"  >  教程
        </a>
      </li>

      <br>
    </ul>
    <h2>我爱你</h2>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: '欢迎进入 Vue.js App'
    }
  }
}
</script>
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
