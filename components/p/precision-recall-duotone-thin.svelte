<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e5rxwxb6q"/><path class="fy1v31b0t"/><path class="qe97cg-lx"/><path class="qbzlhkusu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:precision-recall-duotone-thin" {...props}></Icon>
<style>
:global(.e5rxwxb6q) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 3v18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fy1v31b0t) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 6h6l6 6v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qbzlhkusu) {
  d: path("M6 6h6l6 6v6");
}

:global(.qe97cg-lx) {
  d: path("M3 3v18h18");
}

</style>
