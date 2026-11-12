<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="guj5ndblb"/><path class="x-22ajbkr"/><path class="zqljambho"/><path class="fpr1n1b3q"/><path class="abaosiy3n"/><path class="obcs1cbgf"/><path class="gcs2nkswg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:microphone-2-broken" {...props}></Icon>
<style>
:global(.abaosiy3n) {
  d: path("M7 11L9 11");
}

:global(.fpr1n1b3q) {
  d: path("M7 8L9 8");
}

:global(.gcs2nkswg) {
  d: path("M20 10V11C20 14.012 18.3354 16.6353 15.876 18M4 10V11C4 15.4183 7.58172 19 12 19");
}

:global(.guj5ndblb) {
  d: path("M7 8C7 5.23858 9.23858 3 12 3C14.7614 3 17 5.23858 17 8V11C17 13.7614 14.7614 16 12 16C9.23858 16 7 13.7614 7 11V8Z");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.obcs1cbgf) {
  d: path("M12 19V22");
}

:global(.x-22ajbkr) {
  d: path("M13.5 8L17 8");
}

:global(.zqljambho) {
  d: path("M13.5 11L17 11");
}

</style>
