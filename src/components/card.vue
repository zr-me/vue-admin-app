<template>
  <div style="background-color: #ececec; padding: 20px;">
    <a-row :gutter="16">
      <a-col :span="8">
        <a-card title="商品总览" :bordered="false">
          <p>{{ data.productTotal }}</p>
        </a-card>
      </a-col>
      <a-col :span="8">
        <a-card title="用户总览" :bordered="false">
          <p>{{ data.userTotal }}</p>
        </a-card>
      </a-col>
      <a-col :span="8">
        <a-card title="销售总览" :bordered="false">
          <p>{{ data.saleTotal }}</p>
        </a-card>
      </a-col>
    </a-row>
  </div>
</template>

<script>
export default {
    props: ['data'],
};
</script>
