<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x7kl1kqgv"/><path class="zu-ymbcar"/><path class="yd1dd2b-v"/><path class="ntt8cbcqj"/><path class="ng35sb6yg"/><path class="ys-dg812g"/><path class="pfpu_3ppl"/><path class="eylqpv51p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:air-quality-poor-duotone-thin" {...props}></Icon>
<style>
:global(.eylqpv51p) {
  d: path("M11 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ng35sb6yg) {
  d: path("M3 16a9 9 0 0 1 18 0");
}

:global(.ntt8cbcqj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 8v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pfpu_3ppl) {
  d: path("M12 8v4");
}

:global(.x7kl1kqgv) {
  fill: currentColor;
  d: path("M11 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
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
