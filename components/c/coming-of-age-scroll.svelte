<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iefjp6brw"/><path class="mq8a7k77g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:coming-of-age-scroll" {...props}></Icon>
<style>
:global(.iefjp6brw) {
  d: path("M7.5 7h-2a2 2 0 0 1 0-4h9a2 2 0 0 1 2 2v12h2a2 2 0 0 1 0 4h-9a2 2 0 0 1-2-2Zm0 5h9");
}

:global(.mq8a7k77g) {
  d: path("M10.25 16L12 12l1.75 4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
