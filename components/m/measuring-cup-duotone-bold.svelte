<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wqiv7exrb"/><path class="ltmskg1nl"/><path class="c3b3cobio"/><path class="ozfpplbsk"/><path class="u-cg_ib1f"/><path class="dwqtbeylw"/><path class="zuuhu6bzg"/><path class="nreph_b_j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:measuring-cup-duotone-bold" {...props}></Icon>
<style>
:global(.c3b3cobio) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 15h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dwqtbeylw) {
  d: path("M6 11h6");
}

:global(.ltmskg1nl) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 11h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nreph_b_j) {
  d: path("M17 9a3 3 0 0 1 0 6");
}

:global(.ozfpplbsk) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 9a3 3 0 0 1 0 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u-cg_ib1f) {
  d: path("M5 6v13h12V6");
}

:global(.wqiv7exrb) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 6v13h12V6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zuuhu6bzg) {
  d: path("M6 15h6");
}

</style>
