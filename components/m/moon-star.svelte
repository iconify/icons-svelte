<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hh6dgrm4g"/><path class="iec55d9cd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:moon-star" {...props}></Icon>
<style>
:global(.hh6dgrm4g) {
  d: path("M20 14.75A8.5 8.5 0 1 1 9.25 4A9 9 0 0 0 20 14.75Z");
}

:global(.iec55d9cd) {
  d: path("M16.5 3.5q0 4 4 4q-4 0-4 4q0-4-4-4q4 0 4-4Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
