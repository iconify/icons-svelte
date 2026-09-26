<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ym2fiubju"/><path class="p_ubm5blj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:gallery-horizontal-end-fill" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p_ubm5blj) {
  d: path("M7 5V19M3 7V17");
}

:global(.ym2fiubju) {
  fill: currentColor;
  d: path("M13 2L19 2C20.65685 2 22 3.34315 22 5L22 19C22 20.65685 20.65685 22 19 22L13 22C11.34315 22 10 20.65685 10 19L10 5C10 3.34315 11.34315 2 13 2Z");
  stroke: none;
}

</style>
