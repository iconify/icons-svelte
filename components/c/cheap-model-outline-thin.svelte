<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n6qz8-ogr"/><path class="mc3x0bbgo"/><path class="fxkurobsu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cheap-model-outline-thin" {...props}></Icon>
<style>
:global(.fxkurobsu) {
  d: path("M17.5 10.5v3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mc3x0bbgo) {
  d: path("M13 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

:global(.n6qz8-ogr) {
  d: path("M6.5 8.5 10 12l-3.5 3.5L3 12Z");
}

</style>
