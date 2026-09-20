<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dktry7bqc"/><path class="q_rniwbjv"/><path class="l7hrykbmz"/><path class="xnjbm9uky"/><path class="xqpej4bek"/><path class="l6e2wzbuh"/><path class="qtj-xccdg"/><path class="ne_b8wtyo"/><path class="fsv7g_bbj"/><path class="bo51iypxr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:focus-duotone-thin" {...props}></Icon>
<style>
:global(.bo51iypxr) {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.dktry7bqc) {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.fsv7g_bbj) {
  d: path("M9 21H3v-6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l6e2wzbuh) {
  d: path("M3 9V3h6");
}

:global(.l7hrykbmz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 3h6v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ne_b8wtyo) {
  d: path("M21 15v6h-6");
}

:global(.q_rniwbjv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 9V3h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qtj-xccdg) {
  d: path("M15 3h6v6");
}

:global(.xnjbm9uky) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 15v6h-6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xqpej4bek) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 21H3v-6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
