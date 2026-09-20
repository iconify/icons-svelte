<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qn-h03e3f"/><path class="grqrtqbcz"/><path class="uas13xllp"/><path class="li6wqfgrn"/><path class="crv4i00bu"/><path class="y-rdj5vjt"/><path class="tmdcbizpt"/><path class="l3l5pbb3j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:checkpoint-compare-duotone-bold" {...props}></Icon>
<style>
:global(.crv4i00bu) {
  d: path("M4 3v18");
}

:global(.grqrtqbcz) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 5h6.5v5H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l3l5pbb3j) {
  d: path("M14 9h6.5v5H14");
}

:global(.li6wqfgrn) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 9h6.5v5H14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qn-h03e3f) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tmdcbizpt) {
  d: path("M14 3v18");
}

:global(.uas13xllp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y-rdj5vjt) {
  d: path("M4 5h6.5v5H4");
}

</style>
