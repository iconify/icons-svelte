<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ixaxsccoc"/><path class="p9kyu798w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:gallery-horizontal-start-duotone" {...props}></Icon>
<style>
:global(.ixaxsccoc) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 2L11 2C12.65685 2 14 3.34315 14 5L14 19C14 20.65685 12.65685 22 11 22L5 22C3.34315 22 2 20.65685 2 19L2 5C2 3.34315 3.34315 2 5 2Z");
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p9kyu798w) {
  d: path("M17 5L17 19M21 7L21 17");
}

</style>
