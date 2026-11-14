<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u1l9geasb"/><path class="j_ell-q8u"/><path class="xxo04-bqf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pin-kindergarten" {...props}></Icon>
<style>
:global(.j_ell-q8u) {
  d: path("M3.5 8H16v12.5M16 8l4.5-4.5");
}

:global(.u1l9geasb) {
  d: path("M3.5 8L8 3.5h12.5V16L16 20.5H3.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xxo04-bqf) {
  d: path("M7.25 14.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

</style>
