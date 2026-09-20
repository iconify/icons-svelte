<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ycktj7b1l"/><path class="nxqs9_btq"/><path class="q3rt9cc6p"/><path class="wjuf4tbir"/><path class="woxflvb8t"/><path class="wu-aokb4s"/><path class="h7k_twb0c"/><path class="x1wxn1ypz"/><path class="wm0jgrm5t"/><path class="wy-6ptr_q"/><path class="oi40jf9zq"/><path class="xb0ugqbkt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-negotiation-duotone-thin" {...props}></Icon>
<style>
:global(.h7k_twb0c) {
  d: path("M7.27 3.28a3 3 0 1 1 -2.54 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nxqs9_btq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m13 8 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oi40jf9zq) {
  d: path("M7.5 15v-2.5H10");
}

:global(.q3rt9cc6p) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16.5 9v2.5H14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wjuf4tbir) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m11 16 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wm0jgrm5t) {
  d: path("M16.5 9v2.5H14");
}

:global(.woxflvb8t) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7.5 15v-2.5H10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wu-aokb4s) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19.27 15.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wy-6ptr_q) {
  d: path("m11 16 -3 -3");
}

:global(.x1wxn1ypz) {
  d: path("m13 8 3 3");
}

:global(.xb0ugqbkt) {
  d: path("M19.27 15.28a3 3 0 1 1 -2.54 0");
}

:global(.ycktj7b1l) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7.27 3.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
