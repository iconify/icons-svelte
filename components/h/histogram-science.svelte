<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p8u760b4u"/><path class="pa2w9lbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:histogram-science" {...props}></Icon>
<style>
:global(.p8u760b4u) {
  d: path("M3.5 3v17.5H21");
}

:global(.pa2w9lbnq) {
  d: path("M6.5 20.5V12h4V6h4v3.5h4v11m-8-8.5v8.5m4-11v11");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
