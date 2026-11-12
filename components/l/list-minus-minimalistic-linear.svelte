<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jv514ss1m"/><path class="r5wb7_bnz"/><path class="f8edcu39k"/><path class="y_nlv-nqo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-minus-minimalistic-linear" {...props}></Icon>
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

:global(.jv514ss1m) {
  d: path("M21 6L3 6");
}

:global(.r5wb7_bnz) {
  d: path("M21 11L3 11");
}

:global(.y_nlv-nqo) {
  d: path("M21 18H14");
}

</style>
