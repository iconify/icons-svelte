<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jsatwlp0c"/><path class="r0u_sr26s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:altar-table" {...props}></Icon>
<style>
:global(.jsatwlp0c) {
  d: path("M3 21.5V12h18v9.5");
}

:global(.r0u_sr26s) {
  d: path("m3 16.5l9 2.5l9-2.5m-11-11h4V12h-4ZM12 3h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
