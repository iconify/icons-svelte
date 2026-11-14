<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q5_wtdrvo"/><path class="nr2kwkbiv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cash-bar" {...props}></Icon>
<style>
:global(.nr2kwkbiv) {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

:global(.q5_wtdrvo) {
  d: path("M2.5 3h15L10 11.5L2.5 3m7.5 8.5V21m-4 0h6m2-3a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
