<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="zglivibpc"/><circle class="q669tqbiz"/><circle class="vhjamlbli"/><circle class="z8kp-6bcl"/><circle class="peyn_jvhp"/><path class="oel0kfbvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:fuji-recipe" {...props}></Icon>
<style>
:global(.oel0kfbvq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.748 19.299H8.613m7.835 0h2.797M14.085 24h5.16m-7.86 0H8.613m2.435 4.701H8.613m5.135 0h5.497");
}

:global(.peyn_jvhp) {
  cx: 12.398px;
  cy: 28.701px;
  r: 1.35px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.q669tqbiz) {
  cx: 31.038px;
  cy: 24.405px;
  r: 8.682px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.vhjamlbli) {
  cx: 15.098px;
  cy: 19.299px;
  r: 1.35px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.z8kp-6bcl) {
  cx: 12.735px;
  cy: 24px;
  r: 1.35px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.zglivibpc) {
  width: 39px;
  height: 31px;
  x: 4.567px;
  y: 8.905px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
