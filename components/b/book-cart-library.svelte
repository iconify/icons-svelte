<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vu0hr2bnc"/><path class="we50-eevb"/><path class="qt5-5ob2a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:book-cart-library" {...props}></Icon>
<style>
:global(.qt5-5ob2a) {
  d: path("M5.5 18a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vu0hr2bnc) {
  d: path("M2.5 2.5H4V16h17");
}

:global(.we50-eevb) {
  d: path("M6.5 6.5h4V16h-4Zm9.227-1.186l3.912.831l-2.183 10.271l-3.912-.832Z");
}

</style>
