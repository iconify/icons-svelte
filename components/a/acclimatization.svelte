<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s6uliyj6q"/><path class="g8nj9l4ua"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:acclimatization" {...props}></Icon>
<style>
:global(.g8nj9l4ua) {
  d: path("m13.5 19.5l-6-3.5l4-3.5l-2-3");
}

:global(.s6uliyj6q) {
  d: path("M2.5 19.5L9.5 5l4.5 7.5L16.5 9l5 10.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
