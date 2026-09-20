<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="igcogj_-n"/><path class="ds-ppobhh"/><path class="nvt-cb-fy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fuzz-outline-bold" {...props}></Icon>
<style>
:global(.ds-ppobhh) {
  d: path("m2 14 3 3 3 -3 3 3");
}

:global(.igcogj_-n) {
  d: path("m2 8 3 3 3 -3 3 3");
}

:global(.nvt-cb-fy) {
  d: path("M15 9a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
