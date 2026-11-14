<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mnr58s2jh"/><path class="yzqga_vdc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:court-date" {...props}></Icon>
<style>
:global(.mnr58s2jh) {
  d: path("M3 4h18v17H3Zm5-1.5v4m8-4v4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yzqga_vdc) {
  d: path("m12.763 7.288l4.949 4.949l-2.475 2.475l-4.949-4.949Zm-.013 4.962L7 18");
}

</style>
