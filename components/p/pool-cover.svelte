<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vkkvtbbfm"/><path class="d499e97yr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pool-cover" {...props}></Icon>
<style>
:global(.d499e97yr) {
  d: path("M5.25 14q1.5-1.5 3 0t3 0t3 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vkkvtbbfm) {
  d: path("M2.5 5h19v14h-19Zm10 0l9 9");
}

</style>
