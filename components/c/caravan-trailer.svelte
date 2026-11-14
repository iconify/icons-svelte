<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zu-2oufey"/><path class="x9ctdoqlw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:caravan-trailer" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x9ctdoqlw) {
  d: path("M5.5 17.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM5.25 8h4v3.5h-4ZM12 15.5V8h3.25v7.5");
}

:global(.zu-2oufey) {
  d: path("M2.5 4.5H18v11H2.5ZM18 13h3.5");
}

</style>
