<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xk8a-cc5d"/><path class="isfqeubqe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pin-tram" {...props}></Icon>
<style>
:global(.isfqeubqe) {
  d: path("M8 9h8v5.5H8Zm1-6.5h6m-3 0V6M8 19l-1 2.5m9-2.5l1 2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xk8a-cc5d) {
  d: path("M5 6h14v13H5Z");
}

</style>
