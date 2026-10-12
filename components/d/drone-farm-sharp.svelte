<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="wjjn8xlvb"/><path class="pcxhgbbyh"/><path class="zbatj6iae"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:drone-farm-sharp" {...props}></Icon>
<style>
:global(.pcxhgbbyh) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 12h.01m2.49.5h.01m2.49-.5h.01m-3.76 3h.01m2.49 0h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.wjjn8xlvb) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 5.5h6V9H9zm0 1.75H4.5m10.5 0h4.5m-16.75-3h3.5m11.5 0h3.5m-16.75 0v3m15-3v3");
}

:global(.zbatj6iae) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 21.25h18.5M6 21.25v-2.5m0 0H4.15l-.4-2m2.25 2h1.85l.4-2m3.75 4.5v-2.5m0 0h-1.85l-.4-2m2.25 2h1.85l.4-2m3.75 4.5v-2.5m0 0h-1.85l-.4-2m2.25 2h1.85l.4-2");
}

</style>
