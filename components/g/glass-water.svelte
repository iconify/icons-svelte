<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iecifzbfw"/><path class="ubcuo7btv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:glass-water" {...props}></Icon>
<style>
:global(.iecifzbfw) {
  d: path("M6 5h12l-1.5 15.5h-9Z");
}

:global(.ubcuo7btv) {
  d: path("M6.75 11Q9.5 9.5 12 11t5.25 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
