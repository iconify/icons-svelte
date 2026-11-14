<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pe81_1bib"/><path class="k2wl7ebad"/><path class="l6d6_xbxe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:free-shipping-threshold" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k2wl7ebad) {
  d: path("M5.25 12.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m11 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

:global(.l6d6_xbxe) {
  fill: currentColor;
  d: path("M4.5 17.5h6a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-6a2 2 0 0 1-2-2a2 2 0 0 1 2-2");
}

:global(.pe81_1bib) {
  d: path("M5.125 2.5h6.75A2.625 2.625 0 0 1 14.5 5.125v3.25A2.625 2.625 0 0 1 11.875 11h-6.75A2.625 2.625 0 0 1 2.5 8.375v-3.25A2.625 2.625 0 0 1 5.125 2.5M14.5 5H18l3.5 3.5V11h-7m-10 6.5h15a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2a2 2 0 0 1 2-2");
}

</style>
