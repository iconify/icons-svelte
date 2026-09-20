<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="czo2s0b0e"/><path class="nmwy4lp5x"/><path class="jibzvrd0i"/><path class="d556dgb1h"/><path class="x46tn-bjt"/><path class="wt76_hbmn"/><path class="l9cf9bbmd"/><path class="plqv1xi7k"/><path class="j_z-vb9qy"/><path class="xvmft_b5k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:logout-all-duotone-thin" {...props}></Icon>
<style>
:global(.czo2s0b0e) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 3H3v18h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d556dgb1h) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 15h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j_z-vb9qy) {
  d: path("M10 15h10");
}

:global(.jibzvrd0i) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17.5 6.5 20 9l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l9cf9bbmd) {
  d: path("M10 9h10");
}

:global(.nmwy4lp5x) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 9h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.plqv1xi7k) {
  d: path("M17.5 6.5 20 9l-2.5 2.5");
}

:global(.wt76_hbmn) {
  d: path("M9 3H3v18h6");
}

:global(.x46tn-bjt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17.5 12.5 20 15l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xvmft_b5k) {
  d: path("M17.5 12.5 20 15l-2.5 2.5");
}

</style>
