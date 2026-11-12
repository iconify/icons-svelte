<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ynnqgt8sp"/><path class="toja6_c9f"/><path class="q9lv46bbv"/><path class="y_nlv-nqo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-minus-minimalistic-line-duotone" {...props}></Icon>
<style>
:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q9lv46bbv) {
  d: path("M11 16H3");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.toja6_c9f) {
  d: path("M21 11L3 11");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.y_nlv-nqo) {
  d: path("M21 18H14");
}

:global(.ynnqgt8sp) {
  d: path("M21 6L3 6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
