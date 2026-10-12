<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qt4afwy9g"/><circle class="wertabc3z"/><circle class="q7xtx_x3w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:divide-sign" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q7xtx_x3w) {
  cx: 12px;
  cy: 17.5px;
  r: 1.5px;
}

:global(.qt4afwy9g) {
  d: path("M6.5 12h11");
}

:global(.wertabc3z) {
  cx: 12px;
  cy: 6.5px;
  r: 1.5px;
}

</style>
