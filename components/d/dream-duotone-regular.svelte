<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b0-9-ac4u"/><path class="mdbq_bc-v"/><path class="ke67hpbif"/><path class="iervj3bls"/><path class="koh8ckbdb"/><path class="f-g8rrj2k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dream-duotone-regular" {...props}></Icon>
<style>
:global(.b0-9-ac4u) {
  fill: currentColor;
  d: path("M7 16a4 4 0 0 1 1 -8 5 5 0 0 1 9 1 4 4 0 0 1 0 7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.f-g8rrj2k) {
  d: path("M2 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.iervj3bls) {
  d: path("M7 16a4 4 0 0 1 1 -8 5 5 0 0 1 9 1 4 4 0 0 1 0 7Z");
}

:global(.ke67hpbif) {
  fill: currentColor;
  d: path("M2 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.koh8ckbdb) {
  d: path("M5 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.mdbq_bc-v) {
  fill: currentColor;
  d: path("M5 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
