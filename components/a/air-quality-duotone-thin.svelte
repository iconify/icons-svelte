<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mnw0h9yvg"/><path class="ng35sb6yg"/><path class="ys-dg812g"/><path class="oqr7qbc2i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:air-quality-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mnw0h9yvg) {
  fill: currentColor;
  d: path("M9 13a5 5 0 0 1 7 -5 5 5 0 0 1 -7 5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ng35sb6yg) {
  d: path("M3 16a9 9 0 0 1 18 0");
}

:global(.oqr7qbc2i) {
  d: path("M9 13a5 5 0 0 1 7 -5 5 5 0 0 1 -7 5");
}

:global(.ys-dg812g) {
  d: path("M3 16h18");
}

</style>
