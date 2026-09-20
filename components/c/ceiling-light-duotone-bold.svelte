<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vd0qhnbhi"/><path class="sgr_j7bvk"/><path class="fnf6pdbdu"/><path class="xlnt5q--z"/><path class="m91it7bsg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ceiling-light-duotone-bold" {...props}></Icon>
<style>
:global(.fnf6pdbdu) {
  d: path("M12 3v6");
}

:global(.m91it7bsg) {
  d: path("M9 20h6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sgr_j7bvk) {
  d: path("M8 3h8");
}

:global(.vd0qhnbhi) {
  fill: currentColor;
  d: path("M5 16a7 7 0 0 1 14 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xlnt5q--z) {
  d: path("M5 16a7 7 0 0 1 14 0Z");
}

</style>
