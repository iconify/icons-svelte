<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ii4t72bxj"/><path class="kzcsasbtx"/><path class="g7-k7ab-f"/><path class="kamdbib6v"/><path class="pqojzri_o"/><path class="sno-u_b6h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:laundry-day-duotone-thin" {...props}></Icon>
<style>
:global(.g7-k7ab-f) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 7v10h4V7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ii4t72bxj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 7h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kamdbib6v) {
  d: path("M2 7h20");
}

:global(.kzcsasbtx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 7v7h4V7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pqojzri_o) {
  d: path("M6 7v7h4V7");
}

:global(.sno-u_b6h) {
  d: path("M14 7v10h4V7");
}

</style>
