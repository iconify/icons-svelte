<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hwzp73xdl"/><path class="mz2w6zanc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pharmacy-app" {...props}></Icon>
<style>
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

:global(.mz2w6zanc) {
  d: path("M14.828 9.172za2 2 0 0 1 0 2.828L12 14.828a2 2 0 0 1-2.828 0a2 2 0 0 1 0-2.828L12 9.172a2 2 0 0 1 2.828 0m-4.242 1.414l2.828 2.828M10.5 18.5h3");
}

</style>
