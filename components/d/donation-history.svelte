<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="na1he4b_e"/><path class="rtu_-vu_l"/><path class="j_sim6omd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:donation-history" {...props}></Icon>
<style>
:global(.j_sim6omd) {
  d: path("M7.5 9.75V13a4 2 0 0 0 8 0V9.75");
}

:global(.na1he4b_e) {
  d: path("M11.5 4a8 8 0 1 1-8 8");
}

:global(.rtu_-vu_l) {
  d: path("M17.75 13.75L19.5 12l1.75 1.75m-13.75-4a4 2 0 1 0 8 0a4 2 0 1 0-8 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
