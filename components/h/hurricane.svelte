<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nvebvjbad"/><path class="x3wv0km9z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hurricane" {...props}></Icon>
<style>
:global(.nvebvjbad) {
  d: path("M8 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x3wv0km9z) {
  d: path("M8 12c0-6.5 5.5-9.5 12.5-8.5C16 4 13 5.5 12 8m4 4c0 6.5-5.5 9.5-12.5 8.5C8 20 11 18.5 12 16");
}

</style>
