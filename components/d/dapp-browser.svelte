<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gl5r1muxd"/><path class="x_81gufuq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dapp-browser" {...props}></Icon>
<style>
:global(.gl5r1muxd) {
  d: path("M2.5 3h19v18h-19Zm0 5h19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x_81gufuq) {
  d: path("M7 11h10v7H7Zm5 0v7m-5-3.5h10");
}

</style>
