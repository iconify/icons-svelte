<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sxenkcdlq"/><path class="zqqy_2uco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:camera-back" {...props}></Icon>
<style>
:global(.sxenkcdlq) {
  d: path("M2.5 8a2 2 0 0 1 2-2H8l1.5-2.5h5L16 6h3.5a2 2 0 0 1 2 2v10.5a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zqqy_2uco) {
  d: path("M5.5 9h10v8.5h-10Zm13 4h.01");
}

</style>
