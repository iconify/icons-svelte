<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jmlhv041j"/><path class="b9d1wzyqr"/><path class="fv84_bbid"/><path class="ja7s-m1mr"/><path class="fnf6pdbdu"/><path class="xwissob6k"/><path class="d4f9j2bku"/><path class="x1_r36phd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:drawing-compass-duotone-thin" {...props}></Icon>
<style>
:global(.b9d1wzyqr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 9 -6 6v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d4f9j2bku) {
  d: path("m12 9 6 6v4");
}

:global(.fnf6pdbdu) {
  d: path("M12 3v6");
}

:global(.fv84_bbid) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 9 6 6v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ja7s-m1mr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jmlhv041j) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 3v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x1_r36phd) {
  d: path("M9 12h6");
}

:global(.xwissob6k) {
  d: path("m12 9 -6 6v4");
}

</style>
