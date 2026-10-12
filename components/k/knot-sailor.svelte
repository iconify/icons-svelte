<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h5lh_pbav"/><path class="mcmrpc7tv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:knot-sailor" {...props}></Icon>
<style>
:global(.h5lh_pbav) {
  d: path("M2.75 14.5h5a1.5 1.5 0 0 0 1.5-1.5V6.5a2.75 2.75 0 0 1 5.5 0v6a1.5 1.5 0 0 0 1.5 1.5m2.5 0h2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mcmrpc7tv) {
  d: path("M2.75 7.5H5A1.5 1.5 0 0 1 6.5 9v4m.37 3a5.5 5.5 0 0 0 10.63-2V9.5A1.5 1.5 0 0 1 19 8h2.25");
}

</style>
