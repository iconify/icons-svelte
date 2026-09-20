<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="gww5ooevl"/><circle class="uaiewabrq"/><path class="s82s-6q4s"/><circle class="ejoo13bdy"/><circle class="q5u4mibbp"/><circle class="qc3-pebzk"/><circle class="ux1gt0b0v"/><path class="jzdimietf"/><path class="v170sfb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:lemuroid" {...props}></Icon>
<style>
:global(.ejoo13bdy) {
  cx: 35.9px;
  cy: 16.35px;
  r: 1px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.gww5ooevl) {
  cx: 36px;
  cy: 19.05px;
  r: 7.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.jzdimietf) {
  fill: none;
  stroke: currentColor;
  d: path("M10.7 15.15v2.4H8.2v2.7h2.5v2.4h2.5v-2.4h2.5v-2.7h-2.5v-2.4Z");
}

:global(.q5u4mibbp) {
  cx: 35.9px;
  cy: 21.25px;
  r: 1px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.qc3-pebzk) {
  cx: 33.5px;
  cy: 18.85px;
  r: 1px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.s82s-6q4s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.2 27.25h1.7a4.59 4.59 0 0 1 4.6 4.6a4.59 4.59 0 0 1-4.6 4.6h-1.7a4.59 4.59 0 0 1-4.6-4.6a4.65 4.65 0 0 1 4.6-4.6");
}

:global(.uaiewabrq) {
  cx: 12px;
  cy: 19.05px;
  r: 7.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ux1gt0b0v) {
  cx: 38.4px;
  cy: 18.85px;
  r: 1px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.v170sfb1p) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("m24 33.85l2.9-3.3H21Z");
}

</style>
