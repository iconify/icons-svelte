<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d5czi6rdr"/><path class="g7cpaab_q"/><path class="cfd43lbgp"/><path class="szshe-6ah"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:product-listing-outline-regular" {...props}></Icon>
<style>
:global(.cfd43lbgp) {
  d: path("M7 13h10");
}

:global(.d5czi6rdr) {
  d: path("M3 4a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.g7cpaab_q) {
  d: path("m6 9 3 -3 3 3 2 -2 2 2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.szshe-6ah) {
  d: path("M7 17h10");
}

</style>
