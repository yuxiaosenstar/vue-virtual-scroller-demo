<template>
  <div id="app">
    <RecycleScrollerDemo :list="list" />
  </div>
</template>

<script>
import RecycleScrollerDemo from './components/RecycleScrollerDemo.vue'
export default {
  name: 'App',
  components: {
    RecycleScrollerDemo,
  },
  data() {
    return {
      list: [
        { name: '你好1', id: '1' },
        { name: '你好2', id: '2' },
        { name: '你好3', id: '3' },
        { name: '你好4', id: '4' },
        { name: '你好5', id: '5' },
        { name: '你好6', id: '6' },
        { name: '你好7', id: '7' },
        { name: '你好11', id: '11' },
        { name: '你好12', id: '12' },
        { name: '你好13', id: '13' },
        { name: '你好14', id: '14' },
        { name: '你好15', id: '15' },
        { name: '你好16', id: '16' },
        { name: '你好17', id: '17' },
        { name: '你好21', id: '21' },
        { name: '你好22', id: '22' },
        { name: '你好23', id: '23' },
        { name: '你好24', id: '24' },
        { name: '你好25', id: '25' },
        { name: '你好26', id: '26' },
        { name: '你好27', id: '27' },
        { name: '你好31', id: '31' },
        { name: '你好32', id: '32' },
        { name: '你好33', id: '33' },
        { name: '你好34', id: '34' },
        { name: '你好35', id: '35' },
        { name: '你好36', id: '36' },
        { name: '你好37', id: '37' },
      ],
    }
  },
}
</script>

<style>
#app {
  height: 400px;
}
</style>
