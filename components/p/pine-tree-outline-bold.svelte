<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mlpjr3b8k"/><path class="j42rssb6i"/><path class="e2nq-yvbg"/><path class="gl3o38_gx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pine-tree-outline-bold" {...props}></Icon>
<style>
:global(.e2nq-yvbg) {
  d: path("M12 15v6");
}

:global(.gl3o38_gx) {
  d: path("M8 21h8");
}

:global(.j42rssb6i) {
  d: path("m4 15 8 -8 8 8Z");
}

:global(.mlpjr3b8k) {
  d: path("m6 9 6 -6 6 6Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
