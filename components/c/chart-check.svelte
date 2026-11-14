<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eanni_blz"/><path class="k4zaqqbnc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chart-check" {...props}></Icon>
<style>
:global(.eanni_blz) {
  d: path("M3.5 3v17.5h9.6");
}

:global(.k4zaqqbnc) {
  d: path("M6.5 14L10 8.5l3 2.5l6-6.5M14.5 18l2.5 2.5l4.5-5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
