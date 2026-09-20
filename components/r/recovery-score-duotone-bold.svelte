<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c4fme0p6q"/><path class="gam3cw54g"/><path class="x8irqac3h"/><path class="qe12h9bwz"/><path class="ng35sb6yg"/><path class="ys-dg812g"/><path class="dv6re0b-t"/><path class="ogqckebrf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:recovery-score-duotone-bold" {...props}></Icon>
<style>
:global(.c4fme0p6q) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dv6re0b-t) {
  d: path("M12 16V8");
}

:global(.gam3cw54g) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ng35sb6yg) {
  d: path("M3 16a9 9 0 0 1 18 0");
}

:global(.ogqckebrf) {
  d: path("m9 11 3 -3 3 3");
}

:global(.qe12h9bwz) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 11 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x8irqac3h) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 16V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ys-dg812g) {
  d: path("M3 16h18");
}

</style>
