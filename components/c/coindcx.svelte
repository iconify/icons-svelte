<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oz7x5dbgr"/><path class="k5zfg8x_k"/><rect class="jtmocstwe"/><path class="rk9vi4xjz"/><circle class="cxybsqb4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:coindcx" {...props}></Icon>
<style>
:global(.cxybsqb4v) {
  cx: 28.055px;
  cy: 10.873px;
  r: 0.75px;
  fill: currentColor;
}

:global(.jtmocstwe) {
  width: 5.69px;
  height: 7.539px;
  x: 19.31px;
  y: 13.347px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.845px;
  ry: 2.845px;
}

:global(.k5zfg8x_k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.2 34.76V24.2h2.376a4.62 4.62 0 0 1 4.62 4.62v1.32a4.62 4.62 0 0 1-4.62 4.62z");
}

:global(.oz7x5dbgr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 19.6v18.9a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4zm24.304 4.6L36.8 34.76m0-10.56l-6.996 10.56");
}

:global(.rk9vi4xjz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.055 13.24v7.54m-11.54-1.327a2.845 2.845 0 0 1-5.315-1.412v-1.849a2.845 2.845 0 0 1 2.845-2.845c1.055 0 1.976.575 2.468 1.428M36.8 20.886v-4.694a2.845 2.845 0 0 0-5.69 0v4.694m0-4.694v-2.845m-3.167 17.872v.043a3.498 3.498 0 1 1-6.996 0v-3.564a3.498 3.498 0 1 1 6.996 0v.043");
}

</style>
