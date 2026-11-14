<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hn7tnnbwb"/><path class="farqoqddw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:captions" {...props}></Icon>
<style>
:global(.farqoqddw) {
  d: path("M10 10.25a2 2 0 1 0 0 3.5m6.5-3.5a2 2 0 1 0 0 3.5");
}

:global(.hn7tnnbwb) {
  d: path("M2.5 5h19v14h-19Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
