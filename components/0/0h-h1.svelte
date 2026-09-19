<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="SVGMv5pHcwA" class="fiy0nfkrc"/><path id="SVGPx0sOcVH" class="xx_8_ybnr"/></defs><rect class="v1i_cobsc"/><use href="#SVGMv5pHcwA" class="c-zrgpb5l"/><rect class="bvjlqiy-e"/><use href="#SVGPx0sOcVH" class="c-zrgpb5l"/><rect class="v1i_cobsc"/><use href="#SVGMv5pHcwA" class="c-zrgpb5l"/><rect class="bvjlqiy-e"/><use href="#SVGPx0sOcVH" class="c-zrgpb5l"/><rect class="a68dhd6sv"/><path class="dsm-6hb6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:0h-h1" {...props}></Icon>
<style>
:global(.a68dhd6sv) {
  width: 16.5px;
  height: 16.5px;
  x: 26px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

:global(.bvjlqiy-e) {
  width: 16.5px;
  height: 16.5px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

:global(.c-zrgpb5l) {
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.dsm-6hb6m) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26 19.463h16.5");
}

:global(.fiy0nfkrc) {
  fill: none;
  stroke: currentColor;
  d: path("M5.5 39.963H22");
}

:global(.v1i_cobsc) {
  width: 16.5px;
  height: 16.5px;
  x: 5.5px;
  y: 26px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

:global(.xx_8_ybnr) {
  fill: none;
  stroke: currentColor;
  d: path("M5.5 19.463H22");
}

</style>
