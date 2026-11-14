<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tv79r4bhb"/><path class="doh2mrbia"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:phone-classic" {...props}></Icon>
<style>
:global(.doh2mrbia) {
  d: path("M10 16.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.tv79r4bhb) {
  d: path("M2.5 9V7.5C2.5 5.5 7 4 12 4s9.5 1.5 9.5 3.5V9a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1V7.5h-11V9a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1ZM6 12.5h12l2.5 8h-17Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
