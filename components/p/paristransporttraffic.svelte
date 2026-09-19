<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="d59nbvphv"/><circle class="dcrsu1tcf"/><path class="pit_6rbuz"/><rect class="yi_bitl7e"/><path class="w4x3kebns"/><rect class="eck3g2blg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:paristransporttraffic" {...props}></Icon>
<style>
:global(.d59nbvphv) {
  cx: 15.426px;
  cy: 29.948px;
  r: 2.471px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.dcrsu1tcf) {
  cx: 32.574px;
  cy: 29.948px;
  r: 2.471px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.eck3g2blg) {
  width: 9.371px;
  height: 11.714px;
  x: 25.757px;
  y: 9.531px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.895px;
}

:global(.pit_6rbuz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.843 9.877v22.618a5.39 5.39 0 0 0 5.376 5.377h19.562a5.39 5.39 0 0 0 5.376-5.377V9.877A5.39 5.39 0 0 0 33.781 4.5H14.219a5.39 5.39 0 0 0-5.376 5.377");
}

:global(.w4x3kebns) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.219 37.924L6.758 43.5m27.023-5.576l7.461 5.576");
}

:global(.yi_bitl7e) {
  width: 9.371px;
  height: 11.714px;
  x: 12.872px;
  y: 9.531px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.895px;
}

</style>
