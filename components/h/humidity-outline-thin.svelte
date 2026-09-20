<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kcvg8_brd"/><path class="vny6l674c"/><path class="ep8wlxr3z"/><path class="fz_-scfcf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:humidity-outline-thin" {...props}></Icon>
<style>
:global(.ep8wlxr3z) {
  d: path("m15 19 6 -6");
}

:global(.fz_-scfcf) {
  d: path("M19.5 18.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

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

:global(.vny6l674c) {
  d: path("M14.5 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
