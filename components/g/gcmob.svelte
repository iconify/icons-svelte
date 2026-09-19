<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jrs2o7pbb"/><circle class="t0wmwxbdz"/><ellipse class="z5nb1417j"/><circle class="g9tt1ebcv"/><path class="lcv5u_ben"/><circle class="y3ow_q9-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:gcmob" {...props}></Icon>
<style>
:global(.g9tt1ebcv) {
  cx: 25.542px;
  cy: 21.97px;
  r: 3.213px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.jrs2o7pbb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.504 23.544c6.978 14.744-5.644 17.227-17.695 17.222C10.571 40.761.153 38.48 6.321 23.544");
}

:global(.lcv5u_ben) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.533 29.633c12.46-16.175 3.127-22.45-13.724-22.4c-19.302.058-24.363 5.412-13.722 22.401");
}

:global(.t0wmwxbdz) {
  cx: 23.81px;
  cy: 24px;
  r: 10.685px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.y3ow_q9-r) {
  cx: 23.81px;
  cy: 24px;
  r: 14.834px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.z5nb1417j) {
  cx: 23.81px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.74px;
  ry: 6.021px;
}

</style>
