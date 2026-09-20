<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yix-58bnj"/><path class="moha5wbmp"/><path class="uxyzhxvwz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pii-mask-outline-bold" {...props}></Icon>
<style>
:global(.moha5wbmp) {
  d: path("M22 12a12.5 12.5 0 0 1 -20 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uxyzhxvwz) {
  d: path("M7 12h10");
}

:global(.yix-58bnj) {
  d: path("M2 12a12.5 12.5 0 0 1 20 0");
}

</style>
