<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="k4o_yjbkq"/><circle class="s-tu1sj_i"/><circle class="vqogbbbht"/><circle class="ng_x0-bgy"/><circle class="ofmgw8bwc"/><circle class="tcznf03rc"/><circle class="h3_qgccaj"/><path class="j0n1lugfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:flightradar24" {...props}></Icon>
<style>
:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.h3_qgccaj) {
  cx: 33.449px;
  cy: 8.845px;
  r: 0.75px;
  fill: currentColor;
}

:global(.j0n1lugfa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 24L9.102 39.5");
}

:global(.k4o_yjbkq) {
  cx: 24px;
  cy: 24px;
  r: 14px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ng_x0-bgy) {
  cx: 14.601px;
  cy: 18.911px;
  r: 0.75px;
  fill: currentColor;
}

:global(.ofmgw8bwc) {
  cx: 13.851px;
  cy: 38.75px;
  r: 0.75px;
  fill: currentColor;
}

:global(.s-tu1sj_i) {
  cx: 24px;
  cy: 24px;
  r: 6.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.tcznf03rc) {
  cx: 28.486px;
  cy: 35.47px;
  r: 0.75px;
  fill: currentColor;
}

:global(.vqogbbbht) {
  cx: 24px;
  cy: 24px;
  r: 0.75px;
  fill: currentColor;
}

</style>
