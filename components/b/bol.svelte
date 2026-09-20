<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><rect class="ce90062ku"/><circle class="yighx2hyx"/><path class="od9ntjb8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:bol" {...props}></Icon>
<style>
:global(.ce90062ku) {
  width: 6.025px;
  height: 7.984px;
  x: 21.512px;
  y: 21.793px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.013px;
  ry: 3.013px;
}

:global(.i9clfwm2k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

:global(.od9ntjb8p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.02 17.725V28.27c0 .832.674 1.506 1.506 1.506h.451m-18.905-4.971a3.013 3.013 0 1 1 6.025 0v1.958a3.013 3.013 0 1 1-6.025 0m0 3.013V17.725");
}

:global(.yighx2hyx) {
  cx: 34.178px;
  cy: 29.525px;
  r: 0.75px;
  fill: currentColor;
}

</style>
