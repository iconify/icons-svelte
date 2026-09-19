<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><circle class="xwko2-11o"/><circle class="v1yfv80ss"/><path class="t09jdmbrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:numberogram" {...props}></Icon>
<style>
:global(.j3s9ivbxi) {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

:global(.t09jdmbrz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.299 30.929V17.07L28.7 30.929V17.07");
}

:global(.v1yfv80ss) {
  cx: 35.6px;
  cy: 24px;
  r: 0.75px;
  fill: currentColor;
}

:global(.xwko2-11o) {
  cx: 12.4px;
  cy: 24px;
  r: 0.75px;
  fill: currentColor;
}

</style>
