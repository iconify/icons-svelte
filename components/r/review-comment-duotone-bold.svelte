<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hfygxfboj"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="a1srk3bzo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:review-comment-duotone-bold" {...props}></Icon>
<style>
:global(.a1srk3bzo) {
  d: path("M9 9h6v4h-3.5L9 15.5Z");
}

:global(.d6cu3qpew) {
  d: path("M17 3h4v18h-4");
}

:global(.hfygxfboj) {
  fill: currentColor;
  d: path("M9 9h6v4h-3.5L9 15.5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ldodvk1_f) {
  d: path("M7 3H3v18h4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
