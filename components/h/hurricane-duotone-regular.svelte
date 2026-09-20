<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dktry7bqc"/><path class="d44kz-bgz"/><path class="oxdju1b2k"/><path class="miiipnb-d"/><path class="naut1kwgn"/><path class="bo51iypxr"/><path class="tp8vjxbvr"/><path class="cvdxfrhpf"/><path class="razwus2gf"/><path class="b_28-wbex"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hurricane-duotone-regular" {...props}></Icon>
<style>
:global(.b_28-wbex) {
  d: path("M6 12v8h7");
}

:global(.bo51iypxr) {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.cvdxfrhpf) {
  d: path("M18 12a6 6 0 0 1 -12 0");
}

:global(.d44kz-bgz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 12a6 6 0 0 1 12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dktry7bqc) {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.miiipnb-d) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 12V4h-7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.naut1kwgn) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 12v8h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oxdju1b2k) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 12a6 6 0 0 1 -12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.razwus2gf) {
  d: path("M18 12V4h-7");
}

:global(.tp8vjxbvr) {
  d: path("M6 12a6 6 0 0 1 12 0");
}

</style>
