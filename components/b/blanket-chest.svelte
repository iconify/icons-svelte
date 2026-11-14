<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j4rewo7mw"/><path class="icwywz0wn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:blanket-chest" {...props}></Icon>
<style>
:global(.icwywz0wn) {
  d: path("M10.5 9h3v4.5h-3Z");
}

:global(.j4rewo7mw) {
  d: path("M3 11V8.5a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4V11Zm0 0h18v9.5H3Zm4.5-6.5v16m9-16v16");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
