<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tlqg1hccg"/><path class="x9i7w9bkk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bed-king" {...props}></Icon>
<style>
:global(.tlqg1hccg) {
  d: path("M3.5 12V5a2 2 0 0 1 2-2h13a2 2 0 0 1 2 2v7m-18 0h19v5h-19Zm2 5v3.5m15-3.5v3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x9i7w9bkk) {
  d: path("M6.5 8.5h4V12h-4Zm7 0h4V12h-4Z");
}

</style>
