<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h6ny9xb7b"/><path class="ll9bnb1gg"/><path class="f3r6jjb4a"/><path class="q7xe92bpy"/><path class="camhvtqcl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:align-end-vertical-duotone-bold" {...props}></Icon>
<style>
:global(.camhvtqcl) {
  d: path("M11 14h6v4h-6Z");
}

:global(.f3r6jjb4a) {
  d: path("M20 3v18");
}

:global(.h6ny9xb7b) {
  fill: currentColor;
  d: path("M7 7h10v4H7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ll9bnb1gg) {
  fill: currentColor;
  d: path("M11 14h6v4h-6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.q7xe92bpy) {
  d: path("M7 7h10v4H7Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
