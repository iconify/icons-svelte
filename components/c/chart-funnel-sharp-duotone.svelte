<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="p53xcyb3q"/><path class="mfjihn1sj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-funnel-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.mfjihn1sj) {
  d: path("M6 7L22 7M9 12L19 12M12 17L16 17");
}

:global(.p53xcyb3q) {
  stroke-opacity: 0.4;
  d: path("M3 2L3 21L22 21");
}

</style>
