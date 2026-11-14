<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pvk5qzbuq"/><path class="homo6573s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:repo-security" {...props}></Icon>
<style>
:global(.homo6573s) {
  d: path("m18 13l4 1.5v3c0 2.25-1.75 3.75-4 4.5c-2.25-.75-4-2.25-4-4.5v-3Z");
}

:global(.pvk5qzbuq) {
  d: path("M2.5 8L5 3h10.5L18 8m-6.7 10.5H2.5V8H18v2m-7.75-7v5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
