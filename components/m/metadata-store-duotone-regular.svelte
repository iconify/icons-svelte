<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g7d56fjnv"/><path class="vyks9vbfn"/><path class="rw6ho_bav"/><path class="bytzq2hdx"/><path class="q0ladwbck"/><path class="mdjih2src"/><path class="udhsi7cci"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:metadata-store-duotone-regular" {...props}></Icon>
<style>
:global(.bytzq2hdx) {
  d: path("M6 13h4");
}

:global(.g7d56fjnv) {
  fill: currentColor;
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mdjih2src) {
  d: path("M6 17h4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q0ladwbck) {
  d: path("M14 13h4");
}

:global(.rw6ho_bav) {
  d: path("M2 9h20");
}

:global(.udhsi7cci) {
  d: path("M14 17h4");
}

:global(.vyks9vbfn) {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
