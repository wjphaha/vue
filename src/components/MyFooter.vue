<template>
<footer id="footer">
   <div class="container">
    <ul class="mt-4 d-flex justify-content-between list-unstyled font_color text-center font_small border-bottom pb-5">
      <li><img src="../image/footer/truck-moving.svg" class="mb-2" alt=""><br><span>全场满 ¥99 顺丰包邮（顺丰无法配送的区域将使用 EMS）</span>  </li>
      <li><img src="../image/footer/credit-card.svg" class="mb-2" alt=""><br><span>支持支付宝、微信、银联、银行转账、顺丰到付、花呗和招行分期</span> </li>
      <li><img src="../image/footer/comment-alt-smile.svg" class="mb-2 mr-2"  alt=""><br><span>客服热线：400-700-0303</span> </li>
      <li><img src="../image/footer/siteSealImage.png" class="mb-2"  alt=""></li>
    </ul>
    <!-- 页底的信息 -->
    <div class="row">
      <div class="col-md-10 d-flex justify-content-between mt-4">
        <ul class="list-unstyled font_color font_small">
          <li class="m-2 mb-2 font_black">商城热卖</li>
          <li class="m-2" ><a class="font_color" href="#">“御” Mavic</a> </li>
          <li class="m-2" ><a class="font_color" href="#">“晓” Spark</a> </li>
          <li class="m-2" ><a class="font_color" href="#">精灵 Phantom</a></li>
          <li class="m-2" ><a class="font_color" href="#">灵眸 Osmo</a> </li>
          <li class="m-2" ><a class="font_color" href="#">“悟” Ins pire</a></li>
          <li class="m-2" ><a class="font_color" href="#">如影 Ronin</a> </li>
        </ul>
        <ul class="list-unstyled font_color font_small">
          <li class="m-2 mb-2 font_black">商城项目</li>
          <li class="m-2"><a class="font_color" href="#">翻新机</a> </li>
          <li class="m-2"><a class="font_color" href="#">DJI Select 会员</a> </li>
          <li class="m-2"><a class="font_color" href="#">教育折扣</a> </li>
          <li class="m-2"><a class="font_color" href="#">企业采购</a> </li>
          <li class="m-2"><a class="font_color" href="#">以旧换新</a> </li>
          <li class="m-2"><a class="font_color" href="#">DJI 大疆推广联盟</a> </li>
          <li class="m-2"><a class="font_color" href="#">DJI 大疆商城 App</a> </li>
        </ul>
        <ul class="list-unstyled font_color font_small">
          <li class="m-2 mb-2 font_black">购买指南</li>
          <li class="m-2"><a class="font_color" href="#">支付方式</a></li>
          <li class="m-2"><a class="font_color" href="#">订单帮助</a></li>
          <li class="m-2"><a class="font_color" href="#">发货和物流</a></li>
          <li class="m-2"><a class="font_color" href="#">退换货条款</a></li>
          <li class="m-2"><a class="font_color" href="#">技术支持</a></li>
          <li class="m-2"><a class="font_color" href="#">售后服务政策</a></li>
          <li class="m-2"><a class="font_color" href="#">DJI 币返利计划</a></li>
        </ul>
        <ul class="list-unstyled font_color font_small mr-2">
          <li class="m-1 mb-2 font_black">社区</li>
          <li class="m-2"><a class="font_color" href="#">天空之城</a></li>
          <li class="m-2"><a class="font_color" href="#">DJI 大疆社区</a></li>
          <li class="m-2"><a class="font_color" href="#">购机指南</a></li>
        </ul>
      </div>
      <div class="col-md-2 mt-4">
        <ul class="list-unstyled font_color font_small">
          <li  class="m-1 mb-2 font_black">订阅</li>
          <li>
            <p>第一时间了解我们的促销活动、热销产品和最新信息。</p>
          </li>
          <li class="d-flex ">
            <input type="text" placeholder="请输入你的邮箱" class="border_radius">
            <button class="m-0 bg_btn border-0 outline-0">></button>
          </li>
        </ul>
      </div>
    </div>
    <div class="row border-bottom">
      <div class="col-4 mt-2">
        <ul class="d-flex list-unstyled justify-content-between vertical-align">
          <li><img src="../image/header/logo.svg" alt=""></li>
          <li class="mt-1 font_small font_color">关于我们</li>
          <li class="mt-1 font_small font_color">联系我们</li>
          <li class="mt-1 font_small font_color">招聘精英</li>
          <li class="mt-1 font_small font_color">官方旗舰店</li>
        </ul>
      </div>
      <div class="col-3 mt-2 offset-5">
        <ul class="d-flex list-unstyled justify-content-around">
          <li><img src="../image/footer/weixin.svg" alt=""></li>
          <li><img src="../image/footer/weibo.svg" alt=""></li>
          <li><img src="../image/footer/youku.svg" alt=""></li>
        </ul>
      </div>
    </div>
    <div class="row font_small font_color mt-2">
      <div class="col-md-4 col-sm-12">Copyright © 2019 DJI 大疆创新 版权所有</div>
      <div class="col-md-5 col-sm-12 ">隐私权政策 使用条款 粤ICP备12022215号-11 营业执照 网站地图</div>
      <div class="col-md-3 col-sm-12">网站问题反馈？点击这里</div>
    </div>
  </div>
</footer> 
</template>

<script>
export default {
    data(){
        return{}
    }
}
</script>

<style scoped>
.font_black{
  color:#000;
}
.border_radius{
  border-radius:0.2rem;
}
.bg_btn{
  background-color:#6c7073;
}
.font_color{
  color: #6c7073;
}
a:hover{
  text-decoration: none;
}
.font_small{
  font-size: 0.7rem;
}
</style>
