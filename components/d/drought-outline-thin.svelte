<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ddr0zpdgr"/><path class="zugrvnb7t"/><path class="yfx_djbhn"/><path class="cpo3zsjsl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:drought-outline-thin" {...props}></Icon>
<style>
:global(.cpo3zsjsl) {
  d: path("m16 13 -4 4 4 4");
}

:global(.ddr0zpdgr) {
  d: path("M8 6a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yfx_djbhn) {
  d: path("m6 13 4 4 -4 4");
}

:global(.zugrvnb7t) {
  d: path("M2 13h20");
}

</style>
