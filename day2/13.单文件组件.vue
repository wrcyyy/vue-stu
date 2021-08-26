<template>
  <div>
    <h2>学校名称:{{ schoolName }}</h2>
    <h2>学校地址:{{ address }}</h2>
    <button @click="showName">点我提示学校名</button>
  </div>
</template>
<script>
export default {
  name: "School",
  methods: {
    showName() {
      alert(this.schoolName);
    },
  },
  data() {
    return {
      schoolName: "西南财经大学",
      address: "四川成都温江柳台大道555号",
    };
  },
};
</script>
<style scoped>
</style>