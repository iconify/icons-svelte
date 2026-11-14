<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ltaoqsb7k"/><path class="e1s--tbsk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mail-server" {...props}></Icon>
<style>
:global(.e1s--tbsk) {
  d: path("m14 15.5l3.75 2.5l3.75-2.5");
}

:global(.ltaoqsb7k) {
  d: path("M10.6 15.5H2.5v-11h19v7.2M6.5 10h.01m3.99 0h7m-4 4.5H22v6h-8.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
