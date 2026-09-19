<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zc-42tbgl"/><circle class="xrn88qbra"/><circle class="flff72u_z"/><path class="awrn7ttly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ion-launcher" {...props}></Icon>
<style>
:global(.awrn7ttly) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.416 19.301L24 8.501l18.584 10.8");
}

:global(.flff72u_z) {
  cx: 34.923px;
  cy: 34.964px;
  r: 0.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.xrn88qbra) {
  cx: 24px;
  cy: 23.98px;
  r: 7.21px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.zc-42tbgl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.42 24.081a15.4 15.4 0 0 1-2.066 7.71m-5.644 5.643A15.42 15.42 0 0 1 8.58 24.08");
}

</style>
