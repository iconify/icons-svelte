<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i63wbqccw"/><path class="oo8vqmwgc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:escalator-up" {...props}></Icon>
<style>
:global(.i63wbqccw) {
  d: path("M2.5 20h4v-3h3v-3h3v-3h3V8h6v3l-9 9Z");
}

:global(.oo8vqmwgc) {
  d: path("M2.5 14.5H5L14.5 5h7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
