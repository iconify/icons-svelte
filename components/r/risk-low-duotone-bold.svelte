<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c4fme0p6q"/><path class="gam3cw54g"/><path class="knbretbzw"/><path class="ng35sb6yg"/><path class="ys-dg812g"/><path class="lmbhihbzq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:risk-low-duotone-bold" {...props}></Icon>
<style>
:global(.c4fme0p6q) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gam3cw54g) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.knbretbzw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 16 -5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lmbhihbzq) {
  d: path("m12 16 -5 -5");
}

:global(.ng35sb6yg) {
  d: path("M3 16a9 9 0 0 1 18 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ys-dg812g) {
  d: path("M3 16h18");
}

</style>
