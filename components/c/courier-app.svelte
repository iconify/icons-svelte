<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hwzp73xdl"/><path class="ezhshdb4i"/><path class="vcy8uoxzr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:courier-app" {...props}></Icon>
<style>
:global(.ezhshdb4i) {
  d: path("m12 7l3.25 1.75V13L12 14.75L8.75 13V8.75Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hwzp73xdl) {
  d: path("M10.375 2.5h3.25A4.375 4.375 0 0 1 18 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-3.25A4.375 4.375 0 0 1 6 17.125V6.875A4.375 4.375 0 0 1 10.375 2.5");
}

:global(.vcy8uoxzr) {
  d: path("M8.75 8.75L12 10.5l3.25-1.75M12 10.5v4.25m-1.5 3.75h3");
}

</style>
