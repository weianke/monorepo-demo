<script setup>
import { getUser } from '@anke/utils';
import { Button, Input } from '@anke/components';
console.log(getUser);
getUser().then(res => {
  console.log('res');
});
</script>

<template>
  <div>
    <Button>测试</Button>
    <Input />
  </div>
</template>

<style scoped></style>
