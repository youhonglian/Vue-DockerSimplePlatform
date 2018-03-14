<template>
  <div id="apply">
    {{msg}}
    <hr/>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'apply',
  data () {
    return {
      msg: '应用'
    }
  }
}
</script>