<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="pwnos8bvr"/><circle class="dqynx-bxi"/><rect class="g67athcjt"/><path class="kj6j0gbgg"/><rect class="xko4w4b4d"/><path class="yg4hw6b6t"/><circle class="f2bhypzuh"/><path class="wwpc423oq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:fdroid-alt" {...props}></Icon>
<style>
:global(.dqynx-bxi) {
  cx: 31.008px;
  cy: 15.177px;
  r: 3.503px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.f2bhypzuh) {
  cx: 24.009px;
  cy: 33.325px;
  r: 5.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.g67athcjt) {
  width: 31.315px;
  height: 12.988px;
  x: 8.351px;
  y: 8.683px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.8px;
}

:global(.kj6j0gbgg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 5.834l3.663 3.663");
}

:global(.pwnos8bvr) {
  cx: 16.992px;
  cy: 15.177px;
  r: 3.503px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.wwpc423oq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.45 35.121a3.136 3.136 0 1 0-.171-3.32");
}

:global(.xko4w4b4d) {
  width: 31.315px;
  height: 17.308px;
  x: 8.351px;
  y: 24.671px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.8px;
}

:global(.yg4hw6b6t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.5 5.854l-3.663 3.663");
}

</style>
