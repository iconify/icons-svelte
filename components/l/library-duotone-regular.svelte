<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ub_pbcbdf"/><path class="phjgeccqs"/><path class="gf1u2acan"/><path class="f275eobml"/><path class="woetzacvo"/><path class="dznv025mt"/><path class="taxmbub4q"/><path class="u78lc2bnx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:library-duotone-regular" {...props}></Icon>
<style>
:global(.dznv025mt) {
  d: path("M6 14h12");
}

:global(.f275eobml) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 20h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gf1u2acan) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 17h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.phjgeccqs) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 14h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.taxmbub4q) {
  d: path("M6 17h12");
}

:global(.u78lc2bnx) {
  d: path("M6 20h12");
}

:global(.ub_pbcbdf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m4 12 8 -8 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.woetzacvo) {
  d: path("m4 12 8 -8 8 8");
}

</style>
