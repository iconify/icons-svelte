<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="bn631zbss"/><circle class="g_bx63bby"/><path class="hmv6kubqk"/><path class="hl_5-bctq"/><path class="wtpt6ps-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:id-mobile" {...props}></Icon>
<style>
:global(.bn631zbss) {
  width: 6px;
  height: 20px;
  x: 4.5px;
  y: 18.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3px;
  ry: 3px;
}

:global(.g_bx63bby) {
  cx: 7.5px;
  cy: 12.5px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.hl_5-bctq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.5 19.167H29a4.833 4.833 0 0 1 0 9.667H14.5");
}

:global(.hmv6kubqk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.5 9.5H29c8.008 0 14.5 6.492 14.5 14.5c0 7.067-5.055 12.953-11.747 14.239m-2.991.261H14.5M24.167 24H14.5");
}

:global(.wtpt6ps-w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.5 14.333h10.357m3.106 0H29c5.338 0 9.666 4.328 9.666 9.667c0 1.185-.213 2.32-.603 3.369m-1.473 2.617a9.65 9.65 0 0 1-7.59 3.68H14.5");
}

</style>
