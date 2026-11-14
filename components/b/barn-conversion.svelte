<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jc1d8exii"/><path class="xppoz2b0x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:barn-conversion" {...props}></Icon>
<style>
:global(.jc1d8exii) {
  d: path("M3 21.5V11l3-5.5l6-3l6 3l3 5.5v10.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xppoz2b0x) {
  d: path("M8.5 9.5h7v12h-7Zm3.5 0v12m-3.5-6h7");
}

</style>
