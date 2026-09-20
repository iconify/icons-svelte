<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="eyp-fjbcx"/><path class="o9bf_9bzq"/><path class="qpch75bpm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:body-scale-outline-bold" {...props}></Icon>
<style>
:global(.eyp-fjbcx) {
  d: path("M3 8a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.o9bf_9bzq) {
  d: path("M7 10h3v6H7Z");
}

:global(.qpch75bpm) {
  d: path("M14 10h3v6h-3Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
