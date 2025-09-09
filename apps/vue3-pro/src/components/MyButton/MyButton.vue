<!-- workspace/components/MyButton/MyButton.vue -->
<template>
  <button class="my-button">{{ labelName }}</button>
</template>

<script lang="ts">
import {defineComponent } from 'vue';
export default defineComponent({
  name: 'MyButton',
  props: {
    labelName: {
      type: String,
      default: 'Button'
    }
  }
})
</script>

<style scoped>
.my-button {
  background-color: rgb(228, 13, 13);
  color: white;
  border: none;
  padding: 10px 20px;
  cursor: pointer;
}

</style>

