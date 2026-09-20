<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kcvg8_brd"/><path class="riqqdm93h"/><path class="wnk6eob9l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:humidity-high-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kcvg8_brd) {
  d: path("m8 7 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

:global(.riqqdm93h) {
  d: path("m15 11 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

:global(.wnk6eob9l) {
  d: path("m11 16 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

</style>
