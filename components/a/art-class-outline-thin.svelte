<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wvg9bnb2c"/><path class="cyx--v6br"/><path class="g0co-6h7h"/><path class="lo7kp72nh"/><path class="nnidkxr0z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:art-class-outline-thin" {...props}></Icon>
<style>
:global(.cyx--v6br) {
  d: path("M17 13v7");
}

:global(.g0co-6h7h) {
  d: path("M14 20h6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lo7kp72nh) {
  d: path("M3 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.nnidkxr0z) {
  d: path("M2 17a4 4 0 0 1 8 0");
}

:global(.wvg9bnb2c) {
  d: path("M12 5a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2h-6a2 2 0 0 1 -2 -2Z");
}

</style>
