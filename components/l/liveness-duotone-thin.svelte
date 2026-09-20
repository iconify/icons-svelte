<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f5vgpdbqu"/><path class="t7zftseod"/><path class="wxfc8bn6j"/><path class="oa7ibkb8p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:liveness-duotone-thin" {...props}></Icon>
<style>
:global(.f5vgpdbqu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 6h3l2 -2 4 4 2 -2h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oa7ibkb8p) {
  d: path("M14.32 10a5.5 5.5 0 1 1 -4.64 0");
}

:global(.t7zftseod) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14.32 10a5.5 5.5 0 1 1 -4.64 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wxfc8bn6j) {
  d: path("M5 6h3l2 -2 4 4 2 -2h3");
}

</style>
