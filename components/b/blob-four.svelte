<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lq0-_fbya"/><path class="votxt6b3q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:blob-four" {...props}></Icon>
<style>
:global(.lq0-_fbya) {
  d: path("M7.5 7.5a4.5 4.5 0 0 1 9 0a4.5 4.5 0 0 1 0 9a4.5 4.5 0 0 1-9 0a4.5 4.5 0 0 1 0-9Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.votxt6b3q) {
  d: path("M10.25 7.5A1.75 1.75 0 0 1 12 5.75");
}

</style>
