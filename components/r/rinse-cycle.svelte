<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ruvn1em0i"/><path class="t_ke3d6kh"/><path class="r9na1kb0p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rinse-cycle" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r9na1kb0p) {
  d: path("M9 10.75q1.5-1 3 0t3 0m-6 3.5q1.5-1 3 0t3 0");
}

:global(.ruvn1em0i) {
  d: path("M7.875 2h8.25A4.375 4.375 0 0 1 20.5 6.375v11.25A4.375 4.375 0 0 1 16.125 22h-8.25A4.375 4.375 0 0 1 3.5 17.625V6.375A4.375 4.375 0 0 1 7.875 2");
}

:global(.t_ke3d6kh) {
  d: path("M6 12.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0");
}

</style>
