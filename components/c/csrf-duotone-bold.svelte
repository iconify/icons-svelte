<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="z-nwfukll"/><path class="l4i2yo_dl"/><path class="tuabbzxqz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:csrf-duotone-bold" {...props}></Icon>
<style>
:global(.l4i2yo_dl) {
  d: path("M15 4h5v8l-8 8 -8 -8V4h5Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tuabbzxqz) {
  d: path("m9 11 3 3 5 -5");
}

:global(.z-nwfukll) {
  fill: currentColor;
  d: path("M15 4h5v8l-8 8 -8 -8V4h5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
