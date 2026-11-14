<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wrcg6qhaf"/><path class="chlh2bctx"/><path class="s-li9ut8m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bead-maze" {...props}></Icon>
<style>
:global(.chlh2bctx) {
  d: path("M2.5 14.75h4.75L12 9.25l4.75 5.5h4.75");
}

:global(.s-li9ut8m) {
  d: path("M5.25 14.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM10 9.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4.75 5.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wrcg6qhaf) {
  d: path("M2.5 4.5h19v15h-19Z");
}

</style>
