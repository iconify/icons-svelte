<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ubazlinms"/><path class="fda0jacte"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:crypto-card" {...props}></Icon>
<style>
:global(.fda0jacte) {
  d: path("M14 14.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ubazlinms) {
  d: path("M2.5 5h19v14h-19Zm0 4.5h19M6 15h3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
