<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oz4rn3bss"/><path class="u-a-7fbnu"/><path class="n0k4ov7kr"/><path class="ai7mlsqqn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:carry-on-outline-regular" {...props}></Icon>
<style>
:global(.ai7mlsqqn) {
  d: path("M15 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.n0k4ov7kr) {
  d: path("M7 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oz4rn3bss) {
  d: path("M5 8a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

:global(.u-a-7fbnu) {
  d: path("M10 6V3h4v3");
}

</style>
