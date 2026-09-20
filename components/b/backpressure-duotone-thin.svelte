<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q9hmc9a4v"/><path class="s2ztwmbwx"/><path class="o6a3qip5v"/><path class="leef4tbvz"/><path class="hzi5itbtr"/><path class="f_vuvgsaw"/><path class="bj2hlhbfp"/><path class="ecph9tq5i"/><path class="t3rq50btb"/><path class="fdua8zbmm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:backpressure-duotone-thin" {...props}></Icon>
<style>
:global(.bj2hlhbfp) {
  d: path("M3 12h12");
}

:global(.ecph9tq5i) {
  d: path("M3 18h12");
}

:global(.f_vuvgsaw) {
  d: path("M3 6h12");
}

:global(.fdua8zbmm) {
  d: path("m16 7 3 -3 3 3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hzi5itbtr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 7 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.leef4tbvz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o6a3qip5v) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 18h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q9hmc9a4v) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s2ztwmbwx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t3rq50btb) {
  d: path("M19 4v16");
}

</style>
