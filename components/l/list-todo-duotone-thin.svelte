<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ltk4lt95w"/><path class="b9hsu5b7d"/><path class="uvibyebdw"/><path class="b5p141rkx"/><path class="yt7lrkbdr"/><path class="loif6ccvl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:list-todo-duotone-thin" {...props}></Icon>
<style>
:global(.b5p141rkx) {
  d: path("M11 7.5h10");
}

:global(.b9hsu5b7d) {
  fill: currentColor;
  d: path("M3 14h5v5H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.loif6ccvl) {
  d: path("M11 16.5h10");
}

:global(.ltk4lt95w) {
  fill: currentColor;
  d: path("M3 5h5v5H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.uvibyebdw) {
  d: path("M3 5h5v5H3Z");
}

:global(.yt7lrkbdr) {
  d: path("M3 14h5v5H3Z");
}

</style>
