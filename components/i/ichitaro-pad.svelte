<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="xon4v-xok"/><circle class="fhs8tj_sz"/><circle class="x7sv9egox"/><circle class="kpjzoq2dq"/><path class="iiqxfi0up"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ichitaro-pad" {...props}></Icon>
<style>
:global(.fhs8tj_sz) {
  cx: 24px;
  cy: 12.438px;
  r: 1.812px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.iiqxfi0up) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.5v5.126M14.75 5.5v5.126M33.25 5.5v5.126");
}

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

:global(.kpjzoq2dq) {
  cx: 14.75px;
  cy: 12.438px;
  r: 1.812px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.x7sv9egox) {
  cx: 33.25px;
  cy: 12.438px;
  r: 1.812px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.xon4v-xok) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 21.688h23.125v4.625H5.5z");
}

</style>
