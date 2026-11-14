<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tihk44oem"/><path class="q6slkem0g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cruelty-free" {...props}></Icon>
<style>
:global(.q6slkem0g) {
  d: path("M7.75 6.75a1.75 4 0 1 0 3.5 0a1.75 4 0 1 0-3.5 0Zm5 0a1.75 4 0 1 0 3.5 0a1.75 4 0 1 0-3.5 0ZM10 14.5h.01m3.99 0h.01");
}

:global(.tihk44oem) {
  d: path("M6.5 15a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
