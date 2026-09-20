<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zyr0_hpav"/><path class="dqsvlfbgk"/><path class="y4_6s7b5v"/><path class="wuvisubmw"/><path class="zvb1nubon"/><path class="e36i9zwxh"/><path class="wvvllx1oh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:encyclopedia-duotone-regular" {...props}></Icon>
<style>
:global(.dqsvlfbgk) {
  fill: currentColor;
  d: path("M11 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.e36i9zwxh) {
  d: path("M11 15h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wuvisubmw) {
  d: path("M8 3v18");
}

:global(.wvvllx1oh) {
  d: path("M11 18h6");
}

:global(.y4_6s7b5v) {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.zvb1nubon) {
  d: path("M11 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.zyr0_hpav) {
  fill: currentColor;
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
