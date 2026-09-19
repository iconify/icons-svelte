<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oo9m6i9io"/><rect class="wyaiuccmd"/><path class="u90mw2bxq"/><rect class="qmrel9zah"/><path class="zrf01vweg"/><rect class="oehu3ac5a"/><path class="u7h-rv1bg"/><rect transform="rotate(-10 35.286 22.925)" class="da97wrg_b"/><path class="scte60b2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:pocketbook" {...props}></Icon>
<style>
:global(.da97wrg_b) {
  width: 7.207px;
  height: 27.488px;
  x: 31.682px;
  y: 9.181px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.692px;
  ry: 1.692px;
}

:global(.oehu3ac5a) {
  width: 7.207px;
  height: 27.488px;
  x: 21.462px;
  y: 9.181px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.692px;
  ry: 1.692px;
}

:global(.oo9m6i9io) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 41.559h37");
}

:global(.qmrel9zah) {
  width: 7.207px;
  height: 30.23px;
  x: 14.254px;
  y: 6.441px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.692px;
  ry: 1.692px;
}

:global(.scte60b2k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.245 15.092l7.098-1.251");
}

:global(.u7h-rv1bg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.462 14.335h7.207");
}

:global(.u90mw2bxq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.048 14.335h7.206");
}

:global(.wyaiuccmd) {
  width: 7.207px;
  height: 27.488px;
  x: 7.048px;
  y: 9.181px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.692px;
  ry: 1.692px;
}

:global(.zrf01vweg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.254 11.975h7.208");
}

</style>
