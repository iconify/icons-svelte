<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lwsfc75mg"/><path class="qni2dqmcs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:moon-duotone-bold" {...props}></Icon>
<style>
:global(.lwsfc75mg) {
  fill: currentColor;
  d: path("M18 3a10 10 0 1 0 0 18 12 12 0 0 1 0 -18");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.qni2dqmcs) {
  d: path("M18 3a10 10 0 1 0 0 18 12 12 0 0 1 0 -18");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
