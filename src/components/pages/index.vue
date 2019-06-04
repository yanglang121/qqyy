<template>
  <div class="wrapper">
    <v-top></v-top>
    <v-bottom></v-bottom>
    <v-footer></v-footer>
  </div>
</template>

<script type="text/ecmascript-6">
import API from '../../common/js/api.js';
import t from "../view/top";
import b from "../view/bottom";
import f from "../view/footer";
export default {
  components: {
      "v-top":t,
      "v-bottom":b,
      "v-footer":f,
  },
  props: {},
  data () {
    return {
    };
  },
  watch: {},
  computed: {},
  methods: {},
  mounted () {}
};
</script>
<style scoped>
</style>
