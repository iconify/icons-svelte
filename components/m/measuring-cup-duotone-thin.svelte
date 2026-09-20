<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qtbq5abnn"/><path class="xksi644vv"/><path class="stjf13gff"/><path class="zatfoh9gu"/><path class="u-cg_ib1f"/><path class="dwqtbeylw"/><path class="zuuhu6bzg"/><path class="nreph_b_j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:measuring-cup-duotone-thin" {...props}></Icon>
<style>
:global(.dwqtbeylw) {
  d: path("M6 11h6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nreph_b_j) {
  d: path("M17 9a3 3 0 0 1 0 6");
}

:global(.qtbq5abnn) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 6v13h12V6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.stjf13gff) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 15h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.u-cg_ib1f) {
  d: path("M5 6v13h12V6");
}

:global(.xksi644vv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 11h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zatfoh9gu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 9a3 3 0 0 1 0 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zuuhu6bzg) {
  d: path("M6 15h6");
}

</style>
