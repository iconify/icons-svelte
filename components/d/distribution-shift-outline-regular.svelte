<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mddrthmzf"/><path class="xa0iemevq"/><path class="e9i5dwbzy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:distribution-shift-outline-regular" {...props}></Icon>
<style>
:global(.e9i5dwbzy) {
  d: path("m10.5 13.5 3 -3");
}

:global(.mddrthmzf) {
  d: path("M3 16a4 4 0 0 1 8 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xa0iemevq) {
  d: path("M13 12a4 4 0 0 1 8 0");
}

</style>
