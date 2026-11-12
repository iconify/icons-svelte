<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wr4181b4u"/><path class="vqfns1bta"/><path class="j-a1kqp-o"/><circle class="aaakgqotp"/><path class="i8e2akblu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:card-search-line-duotone" {...props}></Icon>
<style>
:global(.aaakgqotp) {
  cx: 18px;
  cy: 17px;
  r: 3px;
}

:global(.i8e2akblu) {
  d: path("M20.5 19.5L21.5 20.5");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j-a1kqp-o) {
  d: path("M2 10L22 10");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.vqfns1bta) {
  d: path("M10 16H6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.wr4181b4u) {
  d: path("M22 13V12C22 8.22876 22 6.34315 20.8284 5.17157C19.6569 4 17.7712 4 14 4H10C6.22876 4 4.34315 4 3.17157 5.17157C2 6.34315 2 8.22876 2 12C2 15.7712 2 17.6569 3.17157 18.8284C4.34315 20 6.22876 20 10 20H13");
}

</style>
