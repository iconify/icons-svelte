<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="c4jh0ubcp"/><circle class="haj_xguvz"/><circle class="c3ei4cbpw"/><circle class="bmfwqs_og"/><circle class="arv2z5bno"/><circle class="j9o-aswzm"/><circle class="b1060nb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mubi" {...props}></Icon>
<style>
:global(.arv2z5bno) {
  cx: 24px;
  cy: 24px;
  r: 6.17px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.b1060nb2k) {
  cx: 24px;
  cy: 36.33px;
  r: 6.17px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.bmfwqs_og) {
  cx: 24px;
  cy: 11.67px;
  r: 6.17px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.c3ei4cbpw) {
  cx: 11.67px;
  cy: 36.33px;
  r: 6.17px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.c4jh0ubcp) {
  cx: 11.67px;
  cy: 11.67px;
  r: 6.17px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.haj_xguvz) {
  cx: 11.67px;
  cy: 24px;
  r: 6.17px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.j9o-aswzm) {
  cx: 36.33px;
  cy: 24px;
  r: 6.17px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
