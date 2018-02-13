<template>
  <div class='header'>
  <div class="iconfont back">&#xe613;</div>
  <div class="search"><span class="iconfont search-icon">&#xe642;</span>请输入搜索的内容</div>
  <div class="city">乌鲁木齐</div>
  </div>
</template>
<script>
export default {
  name: 'Header'
}
</script>
<style scoped lang="stylus">
@import "../../assets/stylus/varibles.styl";
.header
  display: flex
  height: .88rem
  line-height: .88rem
  background: $bgColor
  color: #fff
  .back
    width: .58rem
    text-align: center
    font-size: .3rem
  .search
    flex: 1
    height: .6rem
    line-height: .6rem
    margin: .14rem .2rem
    padding: 0 0 0 .2rem
    font-size: .2rem
    background: #fff
    border-radius: .1rem
    color: #999
    .search-icon
      padding: .1rem .2rem 0 0
  .city
    position: relative
    padding: 0 .6rem 0 .2rem
    &:before
      position: absolute
      right: .2rem
      top: .35rem
      width: 0;
      height: 0;
      content: "\0020"
      border-top: .14rem solid #fff
      border-right: .14rem solid transparent
      border-bottom: .14rem solid transparent
      border-left: .14rem solid transparent
</style>
