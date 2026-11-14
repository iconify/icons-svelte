<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fvw6uaboz"/><path class="d3dgu_bbg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:due-date-calendar" {...props}></Icon>
<style>
:global(.d3dgu_bbg) {
  d: path("m12 18l-3-3c-1.25-1.25-.75-3 1-3c1 0 1.5.5 2 1.25c.5-.75 1-1.25 2-1.25c1.75 0 2.25 1.75 1 3Z");
}

:global(.fvw6uaboz) {
  d: path("M3 4.5h18V21H3Zm5-2v4m8-4v4M3 9h18");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
