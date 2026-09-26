<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="p53xcyb3q"/><path class="fymyhisch"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-line-up-sharp-duotone" {...props}></Icon>
<style>
:global(.fymyhisch) {
  d: path("M6.7017 15.3356L11 10.5L15 13.5L20.2628 8.6757M15.5 8L21 8L21 13.5");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p53xcyb3q) {
  stroke-opacity: 0.4;
  d: path("M3 2L3 21L22 21");
}

</style>
