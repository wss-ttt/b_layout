<template>
  <el-container>
    <el-aside width="200px">aside</el-aside>
    <el-container>
      <el-header>1</el-header>
      <el-header height="30px">2</el-header>
      <el-main>
        <div class="content">1111</div>
      </el-main>
    </el-container>
  </el-container>
</template>
<script>
  
</script>
<style scoped>
  
  .el-container{
    height: 100vh;
  }
  .el-aside{
    background-color: #ccc;
  } 
  .el-header{
    background-color: green;
  }
  .el-header:nth-child(2){
    background-color: #666;
    border: 1px solid #fff;
  }
  .el-main{
    background-color: yellow;
    overflow: auto;
  }
  .content{
    height: 2000px;
  }
</style>