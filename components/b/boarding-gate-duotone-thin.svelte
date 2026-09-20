<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lf9xn6b8h"/><path class="vlej1p13g"/><path class="z8bkmvbkd"/><path class="wv_foacib"/><path class="pnevpfb0l"/><path class="cq8r84bse"/><path class="srslrxb7v"/><path class="l90ci7bpu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:boarding-gate-duotone-thin" {...props}></Icon>
<style>
:global(.cq8r84bse) {
  d: path("M20 21V4h-4v17");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l90ci7bpu) {
  d: path("m12 9.5 2.5 2.5 -2.5 2.5");
}

:global(.lf9xn6b8h) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 21V4h4v17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pnevpfb0l) {
  d: path("M4 21V4h4v17");
}

:global(.srslrxb7v) {
  d: path("M10 12h4.5");
}

:global(.vlej1p13g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 21V4h-4v17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wv_foacib) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 9.5 2.5 2.5 -2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z8bkmvbkd) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 12h4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
