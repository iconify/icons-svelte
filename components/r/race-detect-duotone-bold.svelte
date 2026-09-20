<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ewhabnb7p"/><path class="s9xdwbcyw"/><path class="nkayykbew"/><path class="uvhovrkef"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:race-detect-duotone-bold" {...props}></Icon>
<style>
:global(.ewhabnb7p) {
  fill: currentColor;
  d: path("M11.5 12a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nkayykbew) {
  d: path("m3 19 7 -7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s9xdwbcyw) {
  d: path("m3 5 7 7");
}

:global(.uvhovrkef) {
  d: path("M11.5 12a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

</style>
