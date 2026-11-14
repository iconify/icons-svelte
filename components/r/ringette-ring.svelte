<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="otocwx4zv"/><path class="h06wv9b3d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ringette-ring" {...props}></Icon>
<style>
:global(.h06wv9b3d) {
  d: path("M7 15a2 2 0 1 0 4 0a2 2 0 1 0-4 0M20.5 2.5l-8 9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.otocwx4zv) {
  d: path("M4 15a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

</style>
