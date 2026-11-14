<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oh_-q4jir"/><path class="jqcwkrrbr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:linkage" {...props}></Icon>
<style>
:global(.jqcwkrrbr) {
  d: path("m9.676 17.52l8.25-14.29l3.898 2.25l-8.25 14.29Zm-4.926-.27h.01m7.74 0h.01M19 5.75h.01");
}

:global(.oh_-q4jir) {
  d: path("M3 15h11.75v4.5H3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
