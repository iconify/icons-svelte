<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c4unwbcyb"/><path class="vzhchmbsi"/><path class="ozc7y4bbr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:adaptation" {...props}></Icon>
<style>
:global(.c4unwbcyb) {
  d: path("M3.5 12a8.5 8.5 0 0 1 16-4");
}

:global(.ozc7y4bbr) {
  d: path("M3.75 18.75L4.5 16l2.75.75M10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vzhchmbsi) {
  d: path("M20.25 5.25L19.5 8l-2.75-.75M20.5 12a8.5 8.5 0 0 1-16 4");
}

</style>
