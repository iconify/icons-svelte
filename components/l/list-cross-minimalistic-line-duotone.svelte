<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="s19aowben"/><path class="f6p-2g58b"/><path class="q9lv46bbv"/><path class="lydqd4-wj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-cross-minimalistic-line-duotone" {...props}></Icon>
<style>
:global(.f6p-2g58b) {
  d: path("M11 11L3 11");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lydqd4-wj) {
  stroke-linejoin: round;
  d: path("M15 16L17.5 13.5M17.5 13.5L20 11M17.5 13.5L20 16M17.5 13.5L15 11");
}

:global(.q9lv46bbv) {
  d: path("M11 16H3");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.s19aowben) {
  d: path("M20 6L3 6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
