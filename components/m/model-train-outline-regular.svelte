<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p30z63bez"/><path class="x4bmljlar"/><path class="wtfq6b2ta"/><path class="rkhcgsbdl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:model-train-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p30z63bez) {
  d: path("M5 5v9h14V9h-5V5Z");
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.wtfq6b2ta) {
  d: path("M14 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.x4bmljlar) {
  d: path("M6 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
