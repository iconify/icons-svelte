<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="snm-237_c"/><path class="w8g9vab9y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:licorice" {...props}></Icon>
<style>
:global(.snm-237_c) {
  d: path("M16.25 12.75a4.25 4.25 0 0 0-8.5 0a6 6 0 0 0 12 0a7.75 7.75 0 0 0-15.5 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w8g9vab9y) {
  d: path("M10.5 12.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

</style>
