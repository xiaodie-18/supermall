<template>
  <tab-bar>
    <tab-bar-item path="/home" active-color="yellow">
      <img slot="item-icon" src="../../assets/img/tabbar/home/home.svg" alt="">
      <img slot="item-icon-active" src="../../assets/img/tabbar/home/home-active.svg" alt="">
      <div slot="item-text">首页</div>
    </tab-bar-item>
    <tab-bar-item path="/all">
      <img slot="item-icon" src="../../assets/img/tabbar/all/all.svg" alt="">
      <img slot="item-icon-active" src="../../assets/img/tabbar/all/all-active.svg" alt="">
      <div slot="item-text">分类</div>
    </tab-bar-item>
    <tab-bar-item path="/cart">
      <img slot="item-icon" src="../../assets/img/tabbar/cart/cart.svg" alt="">
      <img slot="item-icon-active" src="../../assets/img/tabbar/cart/cart-active.svg" alt="">
      <div slot="item-text">购物车</div>
    </tab-bar-item>
    <tab-bar-item path="/my">
      <img slot="item-icon" src="../../assets/img/tabbar/my/my.svg" alt="">
      <img slot="item-icon-active" src="../../assets/img/tabbar/my/my-active.svg" alt="">
      <div slot="item-text">我的</div>
    </tab-bar-item>

  </tab-bar>
</template>

<script>
  import TabBar from '../tabbar/TabBar'
  import TabBarItem from '../tabbar/TabBarItem'
    export default {
        name: "MainTabBar",
        components:{
          TabBar,
          TabBarItem
        }
    }
</script>

<style scoped>

</style>
