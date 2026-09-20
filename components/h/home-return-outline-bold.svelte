<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="f7p-qpb9c"/><path class="rfp-q_b_z"/><path class="lveb61hbp"/><path class="j_t6_obaj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:home-return-outline-bold" {...props}></Icon>
<style>
:global(.f7p-qpb9c) {
  d: path("m3 12 7 -7 7 7");
}

:global(.j_t6_obaj) {
  d: path("M18.5 13.5 16 16l2.5 2.5");
}

:global(.lveb61hbp) {
  d: path("M16 16h6");
}

:global(.rfp-q_b_z) {
  d: path("M5 12v8h10v-8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
