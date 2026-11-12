<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pre11cbbs"/><path class="f8edcu39k"/><path class="lydqd4-wj"/><path class="r9km2ybri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-cross-minimalistic-broken" {...props}></Icon>
<style>
:global(.f8edcu39k) {
  d: path("M11 16H3");
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

:global(.pre11cbbs) {
  d: path("M3 6L13.5 6M17.75 6L20 6");
}

:global(.r9km2ybri) {
  d: path("M11 11L7 11M4.2 11H3");
}

</style>
