<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ynnqgt8sp"/><path class="rhlnpmbpq"/><path class="vi7mzdtvt"/><path class="zbwqridka"/><path class="k2s9xcb6i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-minus-line-duotone" {...props}></Icon>
<style>
:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k2s9xcb6i) {
  d: path("M21 16.5H14");
}

:global(.rhlnpmbpq) {
  d: path("M21 10L3 10");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.vi7mzdtvt) {
  d: path("M11 14L3 14");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.ynnqgt8sp) {
  d: path("M21 6L3 6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.zbwqridka) {
  d: path("M11 18H3");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
