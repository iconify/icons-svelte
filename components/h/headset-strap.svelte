<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v86novb0e"/><path class="yz41x8bfr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:headset-strap" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v86novb0e) {
  d: path("M6 9.5h12a3 3 0 0 1 3 3v3a3 3 0 0 1-3 3h-3L13.5 16h-3L9 18.5H6a3 3 0 0 1-3-3v-3a3 3 0 0 1 3-3Z");
}

:global(.yz41x8bfr) {
  d: path("M3 12.5C-.5 3 24.5 3 21 12.5");
}

</style>
