<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j569280wv"/><path class="ldxs-ebdf"/><path class="ege_vlbjp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:beam-search-outline-thin" {...props}></Icon>
<style>
:global(.ege_vlbjp) {
  d: path("m8 12 6 6h7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j569280wv) {
  d: path("M3 12h5l6 -6h7");
}

:global(.ldxs-ebdf) {
  d: path("M8 12h13");
}

</style>
