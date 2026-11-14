<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ctboolijv"/><path class="r8_fiibdb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:food-bank" {...props}></Icon>
<style>
:global(.ctboolijv) {
  d: path("m2.5 9.5l2 2.5h15l2-2.5M4.5 12v9h15v-9");
}

:global(.r8_fiibdb) {
  d: path("M6 12V9.5a2.5 2.5 0 0 1 5 0V12m2.5-2.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM16 7l.75-2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
