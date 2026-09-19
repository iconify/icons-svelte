<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="hamlhzrfg"/><path class="ygig2abum"/><circle class="j5ahyib_q"/><circle class="o2arujchg"/><circle class="y4n0yubso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:luxchat" {...props}></Icon>
<style>
:global(.hamlhzrfg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.5 17.5a4 4 0 0 1 4-4h13a4 4 0 0 1 4 4v21");
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

:global(.j5ahyib_q) {
  cx: 24px;
  cy: 24px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.o2arujchg) {
  cx: 29px;
  cy: 24px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.y4n0yubso) {
  cx: 19px;
  cy: 24px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ygig2abum) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.5 42.5a4 4 0 0 0 0-8h-13a4 4 0 0 1-4-4v-21a4 4 0 0 0-4-4");
}

</style>
