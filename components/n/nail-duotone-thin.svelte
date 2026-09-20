<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ra78eac8t"/><path class="fj8yl3bfh"/><path class="ibxg-pb4c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:nail-duotone-thin" {...props}></Icon>
<style>
:global(.fj8yl3bfh) {
  d: path("M8 20V10a4 4 0 0 1 8 0v10Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ibxg-pb4c) {
  d: path("M9 13a3 3 0 0 1 6 0");
}

:global(.ra78eac8t) {
  fill: currentColor;
  d: path("M8 20V10a4 4 0 0 1 8 0v10Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
