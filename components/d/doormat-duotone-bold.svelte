<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="obcmadc5g"/><path class="okiuenbyh"/><path class="l0v-b4kbr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:doormat-duotone-bold" {...props}></Icon>
<style>
:global(.l0v-b4kbr) {
  d: path("M8 12h8");
}

:global(.obcmadc5g) {
  fill: currentColor;
  d: path("m3 16 7 -7h4l7 7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.okiuenbyh) {
  d: path("m3 16 7 -7h4l7 7Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
