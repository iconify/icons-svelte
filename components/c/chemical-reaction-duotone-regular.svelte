<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u4n3uw6ij"/><path class="fv3so07ak"/><path class="xgn_w3epb"/><path class="o7bakac8j"/><path class="y8piwob-e"/><path class="v85x73buj"/><path class="rzt8fd71i"/><path class="vezq7pbcc"/><path class="ymhuvfz3p"/><path class="hxtix3e9b"/><path class="y0y0ccsoe"/><path class="cxgftibra"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chemical-reaction-duotone-regular" {...props}></Icon>
<style>
:global(.cxgftibra) {
  d: path("m12 10 2 2 -2 2");
}

:global(.fv3so07ak) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6v11h6V6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hxtix3e9b) {
  d: path("M15 6v11h6V6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o7bakac8j) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 6v11h6V6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rzt8fd71i) {
  d: path("M2 6h8");
}

:global(.u4n3uw6ij) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 6h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v85x73buj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 10 2 2 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vezq7pbcc) {
  d: path("M3 6v11h6V6");
}

:global(.xgn_w3epb) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 6h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y0y0ccsoe) {
  d: path("M10 12h4");
}

:global(.y8piwob-e) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ymhuvfz3p) {
  d: path("M14 6h8");
}

</style>
