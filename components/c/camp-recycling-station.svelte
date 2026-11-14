<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x_2-8xhtw"/><path class="qbrk9ubgz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:camp-recycling-station" {...props}></Icon>
<style>
:global(.qbrk9ubgz) {
  d: path("M13.25 10.5A4 4 0 0 1 16 15l-1-1.5m-.5 3.75a4 4 0 0 1-5 0l1.75-.25M8 15a4 4 0 0 1 2.75-4.5L10 12");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x_2-8xhtw) {
  d: path("M3 6h18M10 6V3.5h4V6M4.5 6L6 20a1.5 1.5 0 0 0 1.5 1.5h9A1.5 1.5 0 0 0 18 20l1.5-14");
}

</style>
