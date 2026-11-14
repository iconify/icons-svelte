<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bf1dmjbmi"/><path class="h9wvsabak"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chicken-coop" {...props}></Icon>
<style>
:global(.bf1dmjbmi) {
  d: path("M3.5 9.5L12 3l8.5 6.5V16h-17Z");
}

:global(.h9wvsabak) {
  d: path("M10 11a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-4 5v5m8-5l7.5 5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
