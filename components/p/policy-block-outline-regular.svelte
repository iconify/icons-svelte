<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y4_6s7b5v"/><path class="kpspt_bpo"/><path class="uxyzhxvwz"/><path class="f-p_drlfa"/><path class="gbehy9bbs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:policy-block-outline-regular" {...props}></Icon>
<style>
:global(.f-p_drlfa) {
  d: path("m10 15 4 4");
}

:global(.gbehy9bbs) {
  d: path("m14 15 -4 4");
}

:global(.kpspt_bpo) {
  d: path("M7 8h10");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.uxyzhxvwz) {
  d: path("M7 12h10");
}

:global(.y4_6s7b5v) {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

</style>
