<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="urfzt0bgl"/><path class="ls6sunbjf"/><path class="wlp3ibbib"/><path class="ky6vhkb9o"/><path class="q9rg3vk5x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:backpack-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ky6vhkb9o) {
  d: path("M9 2v2.5");
}

:global(.ls6sunbjf) {
  d: path("M6 21V9a6 6 0 0 1 12 0v12Z");
}

:global(.q9rg3vk5x) {
  d: path("M15 2v2.5");
}

:global(.urfzt0bgl) {
  fill: currentColor;
  d: path("M6 21V9a6 6 0 0 1 12 0v12Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wlp3ibbib) {
  d: path("M6 13h12");
}

</style>
