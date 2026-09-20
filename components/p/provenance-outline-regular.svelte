<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="aeyekmbly"/><path class="axr3xwb0d"/><path class="yk3ngthye"/><path class="dx_oex_yx"/><path class="umr6jbb1c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:provenance-outline-regular" {...props}></Icon>
<style>
:global(.aeyekmbly) {
  d: path("M3 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.axr3xwb0d) {
  d: path("m7 17 4 -4");
}

:global(.dx_oex_yx) {
  d: path("m15 9 4 -4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.umr6jbb1c) {
  d: path("M18 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.yk3ngthye) {
  d: path("M11 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
