<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jzeve79sx"/><path class="ovtnh7b1i"/><path class="pgh99fbrg"/><path class="kycjhhb3l"/><path class="xug9jccwl"/><path class="ymw3aibdo"/><path class="mhnr27bap"/><path class="fx4s06o2o"/><path class="cwioy_h_g"/><path class="nggq41d_a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:explain-plan-duotone-thin" {...props}></Icon>
<style>
:global(.cwioy_h_g) {
  d: path("M4 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.fx4s06o2o) {
  d: path("M6 13v-3h12v3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jzeve79sx) {
  fill: currentColor;
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.kycjhhb3l) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 7v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mhnr27bap) {
  d: path("M12 7v3");
}

:global(.nggq41d_a) {
  d: path("M16 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ovtnh7b1i) {
  fill: currentColor;
  d: path("M4 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.pgh99fbrg) {
  fill: currentColor;
  d: path("M16 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xug9jccwl) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 13v-3h12v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ymw3aibdo) {
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
