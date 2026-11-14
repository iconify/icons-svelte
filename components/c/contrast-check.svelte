<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tj67z-bgg"/><path class="kyhg65ggd"/><path class="zmkdfnmhj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:contrast-check" {...props}></Icon>
<style>
:global(.kyhg65ggd) {
  d: path("M9 9h12v12H9Z");
}

:global(.tj67z-bgg) {
  fill: currentColor;
  d: path("M3 3h10v10H3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zmkdfnmhj) {
  d: path("M14.5 16.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

</style>
