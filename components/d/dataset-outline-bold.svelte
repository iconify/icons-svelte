<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n09nomjwg"/><path class="x50q_4bdr"/><path class="yih0nfb7c"/><path class="d2gpzsh-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dataset-outline-bold" {...props}></Icon>
<style>
:global(.d2gpzsh-s) {
  d: path("M9 6v12");
}

:global(.n09nomjwg) {
  d: path("M15 6h3a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V9a3 3 0 0 1 3 -3h3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x50q_4bdr) {
  d: path("M3 10h18");
}

:global(.yih0nfb7c) {
  d: path("M3 14h18");
}

</style>
