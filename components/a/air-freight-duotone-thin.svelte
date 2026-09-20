<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fx63l30wc"/><path class="zi0q8abiz"/><path class="dbtxiqbbe"/><path class="r7oo5xbvr"/><path class="y6fpe3bth"/><path class="ae-e09b3w"/><path class="d26wznbgp"/><path class="wm3q5wbwg"/><path class="vblyu6b4h"/><path class="r3snlms8q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:air-freight-duotone-thin" {...props}></Icon>
<style>
:global(.ae-e09b3w) {
  d: path("M3 12h18");
}

:global(.d26wznbgp) {
  d: path("M13 12 7 6");
}

:global(.dbtxiqbbe) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m13 12 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fx63l30wc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r3snlms8q) {
  d: path("m5 12 -2 2");
}

:global(.r7oo5xbvr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 12 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vblyu6b4h) {
  d: path("m5 12 -2 -2");
}

:global(.wm3q5wbwg) {
  d: path("m13 12 -6 6");
}

:global(.y6fpe3bth) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 12 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zi0q8abiz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 12 7 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
