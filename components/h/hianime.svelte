<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="umsuu9btg"/><circle class="hwgqf-bmu"/><path class="plzwfjdhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:hianime" {...props}></Icon>
<style>
:global(.hwgqf-bmu) {
  cx: 30.95px;
  cy: 17.2px;
  r: 0.75px;
  fill: currentColor;
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

:global(.plzwfjdhy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.95 19.926V32.15");
}

:global(.umsuu9btg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.3 16.718V32.15m10.224-15.432V32.15M16.3 24.405h10.224");
}

</style>
