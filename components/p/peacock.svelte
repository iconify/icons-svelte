<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h23gszb-s"/><circle class="fgt2d955m"/><circle class="ohc5vvzzc"/><circle class="p99yhubaj"/><circle class="hrw_sd4-y"/><circle class="j3deuya0f"/><circle class="buvb_i37d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:peacock" {...props}></Icon>
<style>
:global(.buvb_i37d) {
  cx: 37.367px;
  cy: 41.294px;
  r: 0.75px;
  fill: currentColor;
}

:global(.fgt2d955m) {
  cx: 37.367px;
  cy: 6.706px;
  r: 0.75px;
  fill: currentColor;
}

:global(.h23gszb-s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.883 41.158v-25.34a8.976 8.976 0 1 1 17.952 0c0 3.195-1.79 6.457-4.508 7.666c-2.311 1.028-8.916 3.852-8.916 3.852");
}

:global(.hrw_sd4-y) {
  cx: 37.367px;
  cy: 27.459px;
  r: 0.75px;
  fill: currentColor;
}

:global(.j3deuya0f) {
  cx: 37.367px;
  cy: 34.377px;
  r: 0.75px;
  fill: currentColor;
}

:global(.ohc5vvzzc) {
  cx: 37.367px;
  cy: 13.623px;
  r: 0.75px;
  fill: currentColor;
}

:global(.p99yhubaj) {
  cx: 37.367px;
  cy: 20.541px;
  r: 0.75px;
  fill: currentColor;
}

</style>
