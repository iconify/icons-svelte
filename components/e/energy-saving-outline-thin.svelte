<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zo_xbmb4y"/><path class="g-g566bva"/><path class="eob2zbc5p"/><path class="vqwutobjj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:energy-saving-outline-thin" {...props}></Icon>
<style>
:global(.eob2zbc5p) {
  d: path("M9 19h6");
}

:global(.g-g566bva) {
  d: path("M8 10v6h8v-6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vqwutobjj) {
  d: path("M9 13c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
}

:global(.zo_xbmb4y) {
  d: path("M6 10a6 6 0 0 1 12 0");
}

</style>
