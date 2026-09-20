<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zyr0_hpav"/><path class="lir4n8byf"/><path class="y4_6s7b5v"/><path class="kpspt_bpo"/><path class="uxyzhxvwz"/><path class="r6zx28b8c"/><path class="pg0en1bcd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:exam-duotone-bold" {...props}></Icon>
<style>
:global(.kpspt_bpo) {
  d: path("M7 8h10");
}

:global(.lir4n8byf) {
  fill: currentColor;
  d: path("M13 17a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.pg0en1bcd) {
  d: path("M13 17a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.r6zx28b8c) {
  d: path("M7 16h6");
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

:global(.y4_6s7b5v) {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.zyr0_hpav) {
  fill: currentColor;
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
