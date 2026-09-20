<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f7p-qpb9c"/><path class="rfp-q_b_z"/><path class="lveb61hbp"/><path class="j_t6_obaj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:home-return-outline-regular" {...props}></Icon>
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

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rfp-q_b_z) {
  d: path("M5 12v8h10v-8");
}

</style>
