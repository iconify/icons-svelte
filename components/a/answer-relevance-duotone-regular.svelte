<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rc-rl3bzt"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="j5rx0rbrw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:answer-relevance-duotone-regular" {...props}></Icon>
<style>
:global(.ffw_pwyfz) {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

:global(.j5rx0rbrw) {
  d: path("M7 7h6v4H9.5L7 13.5Z");
}

:global(.kfdmhd64i) {
  d: path("m15 15 6 6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rc-rl3bzt) {
  fill: currentColor;
  d: path("M7 7h6v4H9.5L7 13.5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
