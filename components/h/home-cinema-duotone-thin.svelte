<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b46x6x-hs"/><path class="e03sywmba"/><path class="jaoga6bck"/><path class="cl583ybqk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:home-cinema-duotone-thin" {...props}></Icon>
<style>
:global(.b46x6x-hs) {
  fill: currentColor;
  d: path("M3 4v10h18V4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.cl583ybqk) {
  d: path("M13 20a3 3 0 0 1 6 0");
}

:global(.e03sywmba) {
  d: path("M3 4v10h18V4Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jaoga6bck) {
  d: path("M5 20a3 3 0 0 1 6 0");
}

</style>
