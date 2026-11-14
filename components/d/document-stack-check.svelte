<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i8vbytxuu"/><path class="e9fltbcec"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:document-stack-check" {...props}></Icon>
<style>
:global(.e9fltbcec) {
  d: path("m14.75 18l2 2L21 15.75");
}

:global(.i8vbytxuu) {
  d: path("M14.3 21.5H3.5v-13h17v3.8m0 7.9v1.3h-1.3M5.5 5.5h13m-11-3h9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
