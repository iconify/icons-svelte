<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u67c_sdph"/><path class="ze82kx64m"/><path class="nr2kwkbiv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:account-business" {...props}></Icon>
<style>
:global(.nr2kwkbiv) {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

:global(.u67c_sdph) {
  d: path("M11.5 20h-9V7h19v5.8M8.5 7V5.5A1.5 1.5 0 0 1 10 4h4a1.5 1.5 0 0 1 1.5 1.5V7m-13 5h19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ze82kx64m) {
  d: path("M14 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

</style>
