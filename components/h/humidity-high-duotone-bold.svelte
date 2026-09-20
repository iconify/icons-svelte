<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="uhsn5wb8z"/><path class="djz5e420y"/><path class="ildco7byy"/><path class="kcvg8_brd"/><path class="riqqdm93h"/><path class="wnk6eob9l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:humidity-high-duotone-bold" {...props}></Icon>
<style>
:global(.djz5e420y) {
  fill: currentColor;
  d: path("m15 11 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ildco7byy) {
  fill: currentColor;
  d: path("m11 16 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.kcvg8_brd) {
  d: path("m8 7 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

:global(.riqqdm93h) {
  d: path("m15 11 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uhsn5wb8z) {
  fill: currentColor;
  d: path("m8 7 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wnk6eob9l) {
  d: path("m11 16 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

</style>
