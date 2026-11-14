<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="md2g9nvaz"/><path class="f25ej6b8z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:highlight-color" {...props}></Icon>
<style>
:global(.f25ej6b8z) {
  fill: currentColor;
  d: path("M6 18h12v3H6Z");
}

:global(.md2g9nvaz) {
  d: path("m6 15l6-12l6 12m-9.75-4.5h7.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
