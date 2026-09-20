<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yxjvqtiry"/><path class="j710mobqc"/><path class="qe97cg-lx"/><path class="sfefbpbuh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:novelty-effect-duotone-bold" {...props}></Icon>
<style>
:global(.j710mobqc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m5 15 5 -5 4 4h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qe97cg-lx) {
  d: path("M3 3v18h18");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sfefbpbuh) {
  d: path("m5 15 5 -5 4 4h5");
}

:global(.yxjvqtiry) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 3v18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
