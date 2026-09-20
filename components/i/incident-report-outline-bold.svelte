<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="y4_6s7b5v"/><path class="wuvisubmw"/><path class="ov6_zwbsl"/><path class="m-9merm8x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:incident-report-outline-bold" {...props}></Icon>
<style>
:global(.m-9merm8x) {
  d: path("M13 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ov6_zwbsl) {
  d: path("M14 9v3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wuvisubmw) {
  d: path("M8 3v18");
}

:global(.y4_6s7b5v) {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

</style>
