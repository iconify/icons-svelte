<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yx86wwbnp"/><rect class="o-u6d5rvb"/><path class="lbtmicb7f"/><circle class="mtg6nxbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:invest" {...props}></Icon>
<style>
:global(.lbtmicb7f) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.562 16.188h10.067M5.5 19.974h10.067");
}

:global(.mtg6nxbyk) {
  cx: 12.056px;
  cy: 8.589px;
  r: 1.84px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.o-u6d5rvb) {
  width: 13.13px;
  height: 11.358px;
  x: 5.5px;
  y: 12.402px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.181px;
}

:global(.yx86wwbnp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.504 41.251H42.5V28.153M7.434 37.688L22.424 22.7l5.108 5.108L42.5 12.84v11.056M31.359 12.839H42.5");
}

</style>
