<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xa771-t-o"/><path class="qd95ekbzt"/><path class="ugdbidcqi"/><path class="b5rl3obyb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-bookmark-duotone-bold" {...props}></Icon>
<style>
:global(.b5rl3obyb) {
  d: path("M9 8h6v8l-3 -3 -3 3Z");
}

:global(.qd95ekbzt) {
  fill: currentColor;
  d: path("M9 8h6v8l-3 -3 -3 3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ugdbidcqi) {
  d: path("M16.23 2.94a10 10 0 1 1 -8.46 0");
}

:global(.xa771-t-o) {
  fill: currentColor;
  d: path("M16.23 2.94a10 10 0 1 1 -8.46 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
