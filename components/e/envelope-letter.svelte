<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x4m-6rbyr"/><path class="fx6xsklwp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:envelope-letter" {...props}></Icon>
<style>
:global(.fx6xsklwp) {
  d: path("M10 13a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x4m-6rbyr) {
  d: path("M2.5 4.5h19v15h-19Zm0 1.5l7.25 6M21.5 6l-7.25 6");
}

</style>
