<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g6ulkabjn"/><path class="mxytal0pg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:macro-shot" {...props}></Icon>
<style>
:global(.g6ulkabjn) {
  d: path("M2.5 2.5h19v19h-19Z");
}

:global(.mxytal0pg) {
  d: path("M13.75 9.5a2.5 2.5 0 1 1 1 3.5A2.5 2.5 0 1 1 12 15a2.5 2.5 0 1 1-2.75-2a2.5 2.5 0 1 1 1-3.5a2.5 2.5 0 1 1 3.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
