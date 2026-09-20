<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qlvopac9f"/><path class="vg1ko9_4w"/><path class="ycd9h4byt"/><path class="qzipu_nba"/><path class="crv4i00bu"/><path class="y-rdj5vjt"/><path class="tmdcbizpt"/><path class="l3l5pbb3j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:checkpoint-compare-duotone-regular" {...props}></Icon>
<style>
:global(.crv4i00bu) {
  d: path("M4 3v18");
}

:global(.l3l5pbb3j) {
  d: path("M14 9h6.5v5H14");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qlvopac9f) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qzipu_nba) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 9h6.5v5H14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tmdcbizpt) {
  d: path("M14 3v18");
}

:global(.vg1ko9_4w) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 5h6.5v5H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y-rdj5vjt) {
  d: path("M4 5h6.5v5H4");
}

:global(.ycd9h4byt) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
