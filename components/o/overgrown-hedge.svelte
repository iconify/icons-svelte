<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jt2tn6g0v"/><path class="juj6a7bmr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:overgrown-hedge" {...props}></Icon>
<style>
:global(.jt2tn6g0v) {
  d: path("M3 20v-6c0-2.5 2-4 4-3.5c1-2 3.5-2.5 5-1.5c1.5-1 4-.5 5 1.5c2-.5 4 1 4 3.5v6Z");
}

:global(.juj6a7bmr) {
  d: path("M7 10.5q.5-4.5-4-5q-.5 4.5 4 5Zm10 0q-.5-5.5 4-7q1 5.5-4 7ZM12 9V5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
