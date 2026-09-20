<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zu-ymbcar"/><path class="yd1dd2b-v"/><path class="kj325sbuw"/><path class="ptyyi6psl"/><path class="ng35sb6yg"/><path class="ys-dg812g"/><path class="lmbhihbzq"/><path class="xmg9uv4ey"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pressure-falling-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kj325sbuw) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 16 -5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lmbhihbzq) {
  d: path("m12 16 -5 -5");
}

:global(.ng35sb6yg) {
  d: path("M3 16a9 9 0 0 1 18 0");
}

:global(.ptyyi6psl) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10.5 11H7v3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xmg9uv4ey) {
  d: path("M10.5 11H7v3.5");
}

:global(.yd1dd2b-v) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ys-dg812g) {
  d: path("M3 16h18");
}

:global(.zu-ymbcar) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
