<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tzdfp4-do"/><path class="ufzn_r3vk"/><path class="m1oey3b_j"/><path class="m-9jjacoy"/><path class="w5i79a2na"/><path class="wy2n5sbyh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:nurse-duotone-bold" {...props}></Icon>
<style>
:global(.m-9jjacoy) {
  d: path("M8 6V3h8v3");
}

:global(.m1oey3b_j) {
  d: path("M5.4 17a6.6 6.6 0 0 1 13.2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tzdfp4-do) {
  fill: currentColor;
  d: path("M9 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ufzn_r3vk) {
  d: path("M9 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.w5i79a2na) {
  d: path("M12 14v4");
}

:global(.wy2n5sbyh) {
  d: path("M10 16h4");
}

</style>
