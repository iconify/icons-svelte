<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r14em7b4l"/><path class="ur9jjfbgq"/><path class="zx1hmsoqu"/><path class="i5be34b7d"/><path class="fav0kibck"/><path class="eex8q3rzp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bench-run-duotone-regular" {...props}></Icon>
<style>
:global(.eex8q3rzp) {
  d: path("M17 12h2.5");
}

:global(.fav0kibck) {
  d: path("M17 9.5V12");
}

:global(.i5be34b7d) {
  d: path("M13 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r14em7b4l) {
  fill: currentColor;
  d: path("m4 6 7 7 -7 7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ur9jjfbgq) {
  fill: currentColor;
  d: path("M13 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zx1hmsoqu) {
  d: path("m4 6 7 7 -7 7Z");
}

</style>
