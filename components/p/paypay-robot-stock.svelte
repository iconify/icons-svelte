<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="gdowrtbwu"/><rect class="no-8ukbut"/><circle class="ou_vo8bty"/><circle class="tohduac1r"/><circle class="zga3lhvps"/><path class="w0mn_4ern"/><circle class="r392uhbcl"/><path class="y50yx_v1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:paypay-robot-stock" {...props}></Icon>
<style>
:global(.gdowrtbwu) {
  width: 19.5px;
  height: 13.5px;
  x: 14.25px;
  y: 9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

:global(.no-8ukbut) {
  width: 19.5px;
  height: 13.5px;
  x: 14.25px;
  y: 24.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

:global(.ou_vo8bty) {
  cx: 7.5px;
  cy: 35.5px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.r392uhbcl) {
  cx: 40.5px;
  cy: 19.5px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.tohduac1r) {
  cx: 18.75px;
  cy: 15.75px;
  r: 1.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.w0mn_4ern) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.5 32.5a5 5 0 0 1 5-5");
}

:global(.y50yx_v1o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.5 22.5a5 5 0 0 1-5 5");
}

:global(.zga3lhvps) {
  cx: 29.25px;
  cy: 15.75px;
  r: 1.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
