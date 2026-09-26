<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="d098hyf_v"/><path class="xeb-fib6w"/><path class="ciu-kx8bj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:podium-3-sharp-fill" {...props}></Icon>
<style>
:global(.ciu-kx8bj) {
  d: path("M14.3 2L18.7 2L16.728 4.334C18.7 4.334 18.7 4.9706 18.7 5.9254C18.7 7.4107 15.606 7.1985 15.3 6.2437L14.9948 5.2914");
}

:global(.d098hyf_v) {
  fill: currentColor;
  d: path("M4 22L4 18.5L9 18.5L9 15L14 15L14 11.5L20 11.5L20 22L4 22Z");
  stroke: none;
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xeb-fib6w) {
  stroke-linejoin: miter;
  d: path("M1 22L23 22M4 22L4 18.5L9 18.5L9 15L14 15L14 11.5L20 11.5L20 22L4 22Z");
}

</style>
