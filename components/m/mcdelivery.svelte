<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="v6d3ekose"/><ellipse class="ph-ttqbnl"/><ellipse class="rahxnpbvi"/><circle class="uajv8_80z"/><circle class="f500gnbut"/><circle class="k9b9w2b0e"/><circle class="j1a5owade"/><circle class="b6astptrg"/><circle class="itl1kv80e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mcdelivery" {...props}></Icon>
<style>
:global(.b6astptrg) {
  cx: 19.763px;
  cy: 38.574px;
  r: 0.75px;
  fill: currentColor;
}

:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.f500gnbut) {
  cx: 28.022px;
  cy: 38.574px;
  r: 0.75px;
  fill: currentColor;
}

:global(.itl1kv80e) {
  cx: 17.207px;
  cy: 38.105px;
  r: 0.75px;
  fill: currentColor;
}

:global(.j1a5owade) {
  cx: 22.615px;
  cy: 38.726px;
  r: 0.75px;
  fill: currentColor;
}

:global(.k9b9w2b0e) {
  cx: 25.246px;
  cy: 38.726px;
  r: 0.75px;
  fill: currentColor;
}

:global(.ph-ttqbnl) {
  cx: 13.229px;
  cy: 36.752px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.629px;
  ry: 1.594px;
}

:global(.rahxnpbvi) {
  cx: 34.764px;
  cy: 36.752px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.629px;
  ry: 1.594px;
}

:global(.uajv8_80z) {
  cx: 30.799px;
  cy: 38.147px;
  r: 0.75px;
  fill: currentColor;
}

:global(.v6d3ekose) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.5 32.272c0-5.785-1.511-23.402-6.306-23.402S24 22.16 24 30.448C24 22.16 22.602 8.87 17.807 8.87S11.5 26.486 11.5 32.272");
}

</style>
