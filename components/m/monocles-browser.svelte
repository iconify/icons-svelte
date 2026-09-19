<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h77h9ybjd"/><circle class="evlrowctj"/><path class="uqh8d-xiu"/><circle class="jh0w3ub4s"/><circle class="gwniu4bay"/><circle class="hl-vzmb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:monocles-browser" {...props}></Icon>
<style>
:global(.evlrowctj) {
  cx: 33.53px;
  cy: 17.247px;
  r: 5.224px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.gwniu4bay) {
  cx: 5.262px;
  cy: 17.247px;
  r: 0.75px;
  fill: currentColor;
}

:global(.h77h9ybjd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.005 29.023s1.874-1.47 3.021-.909c3.847 1.881 5.53 7.56 13.556 3.215c-5.478 9.967-14.201 5.72-16.577 2.231c-2.375 3.489-11.098 7.736-16.576-2.23c8.026 4.343 9.709-1.335 13.556-3.216c1.147-.56 3.02.909 3.02.909m18.735-.66v-6.9");
}

:global(.hl-vzmb5h) {
  cx: 42.74px;
  cy: 17.247px;
  r: 0.75px;
  fill: currentColor;
}

:global(.jh0w3ub4s) {
  cx: 14.47px;
  cy: 17.247px;
  r: 5.224px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.uqh8d-xiu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.261 28.363v-6.9");
}

</style>
