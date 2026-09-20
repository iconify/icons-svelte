<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y3q_wpbez"/><path class="f23oww7ng"/><path class="yz8w-bcjg"/><path class="y8cxqebzo"/><path class="ob3bf9b2i"/><path class="r4bxr4bnm"/><path class="ljz_vjbfq"/><path class="phj3jm8ef"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:label-queue-duotone-thin" {...props}></Icon>
<style>
:global(.f23oww7ng) {
  fill: currentColor;
  d: path("M5 14h10l3.5 3.5L15 21H5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ljz_vjbfq) {
  d: path("M7 6.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ob3bf9b2i) {
  d: path("M5 3h10l3.5 3.5L15 10H5Z");
}

:global(.phj3jm8ef) {
  d: path("M7 17.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.r4bxr4bnm) {
  d: path("M5 14h10l3.5 3.5L15 21H5Z");
}

:global(.y3q_wpbez) {
  fill: currentColor;
  d: path("M5 3h10l3.5 3.5L15 10H5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.y8cxqebzo) {
  fill: currentColor;
  d: path("M7 17.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.yz8w-bcjg) {
  fill: currentColor;
  d: path("M7 6.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
