<script>
import { init } from "ityped"
export default {
  mounted() {
    init(this.$refs.describe, {
      strings: ["今天是4月10日","不","今天是4月7日","你又被我骗到了吧","这些话写于3月31日凌晨","我们在一起的一年里，我们吵吵闹闹，我们互相理解着对方","我是一个挺不稳重的人，TIPS：宝贝应该不这么觉得吧？","但当我认定你就是我这辈子最想照顾的人后","我想要成为你心中最可靠的另一半","你愿意嫁给我吗？"],
      //optional
      typeSpeed: 90, //default
      //optional
      backSpeed: 90, //default
      //optional
      startDelay: 1000, //default
      //optional
      backDelay: 1000, //default
      //optional
      loop: false, //default
      //optional
      showCursor: true, //default
      cursorChar: ""
    })
  }
}
</script>

<template>
  <div class="pt-24" style="font-size:40px">
  <h1 ref="title" style="color:black;"></h1>
  <span ref="describe"></span>
</div>
</template>
