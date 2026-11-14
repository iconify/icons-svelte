<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ezka2rber"/><path class="wz6_99bsl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:presentation-board" {...props}></Icon>
<style>
:global(.ezka2rber) {
  d: path("M3 3h18v12H3Zm5 12l-2 6.5M16 15l2 6.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wz6_99bsl) {
  d: path("m6.5 11.5l3.5-3l3 1.5l4.5-4");
}

</style>
