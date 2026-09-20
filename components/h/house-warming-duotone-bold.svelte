<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="m-yo_2b4g"/><path class="syw8dymcb"/><path class="rsz3y4a_c"/><path class="u-niy3p1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:house-warming-duotone-bold" {...props}></Icon>
<style>
:global(.m-yo_2b4g) {
  fill: currentColor;
  d: path("M4 19v-7l7 -7 7 7v7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rsz3y4a_c) {
  d: path("M4 19v-7l7 -7 7 7v7Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.syw8dymcb) {
  fill: currentColor;
  d: path("M11 16c-2 -1 -2 -4 0 -5 2 1 2 4 0 5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.u-niy3p1t) {
  d: path("M11 16c-2 -1 -2 -4 0 -5 2 1 2 4 0 5");
}

</style>
