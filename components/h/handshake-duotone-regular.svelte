<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rsea1pbos"/><path class="ph8xawbhr"/><path class="jbm95jy8g"/><path class="xduesxbwm"/><path class="r9e3konmz"/><path class="hddsmsbuv"/><path class="zuquf0b8s"/><path class="fcstqn4mf"/><path class="f8gsx7b5s"/><path class="qs69rnufu"/><path class="xqfhg19ie"/><path class="q9rcsymqn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:handshake-duotone-regular" {...props}></Icon>
<style>
:global(.f8gsx7b5s) {
  d: path("M6 8h12");
}

:global(.fcstqn4mf) {
  d: path("M18 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hddsmsbuv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m6 16 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jbm95jy8g) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 8h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ph8xawbhr) {
  fill: currentColor;
  d: path("M18 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.q9rcsymqn) {
  d: path("m6 16 3 3");
}

:global(.qs69rnufu) {
  d: path("m18 8 -3 -3");
}

:global(.r9e3konmz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 16H6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rsea1pbos) {
  fill: currentColor;
  d: path("M2 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xduesxbwm) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m18 8 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xqfhg19ie) {
  d: path("M18 16H6");
}

:global(.zuquf0b8s) {
  d: path("M2 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
