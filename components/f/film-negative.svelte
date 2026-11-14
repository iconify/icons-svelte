<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rfzlusfnz"/><path class="neee3pb_i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:film-negative" {...props}></Icon>
<style>
:global(.neee3pb_i) {
  d: path("m2.5 18.5l3-3.5l3.25 3.5L12 15l3.25 3.5L18.5 15l3 3.5");
}

:global(.rfzlusfnz) {
  d: path("M2.5 5.5h19v13h-19Zm0 3h19m-12.75 0v10m6.5-10v10");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
