<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="y4_6s7b5v"/><path class="fhi210b_d"/><path class="zaehmnb6i"/><path class="wg8_ddc1f"/><path class="b9ex0_kla"/><path class="uc661cbro"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:book-index-outline-bold" {...props}></Icon>
<style>
:global(.b9ex0_kla) {
  d: path("M6 16h6");
}

:global(.fhi210b_d) {
  d: path("M13 5v14");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uc661cbro) {
  d: path("M15 10h4");
}

:global(.wg8_ddc1f) {
  d: path("M6 12h6");
}

:global(.y4_6s7b5v) {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.zaehmnb6i) {
  d: path("M6 8h6");
}

</style>
