<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e8v7ax2lp"/><path class="j1j4yzvdj"/><path class="k4_bwgbwn"/><path class="chml-dbhf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:branch-step-duotone-regular" {...props}></Icon>
<style>
:global(.chml-dbhf) {
  d: path("M12.5 14.5 19 21");
}

:global(.e8v7ax2lp) {
  fill: currentColor;
  d: path("M5 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.j1j4yzvdj) {
  d: path("M5 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.k4_bwgbwn) {
  d: path("M12.5 9.5 19 3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
