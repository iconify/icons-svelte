<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vdxipibqw"/><path class="yacyzm0cg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:gallery-vertical-start-two-tone" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vdxipibqw) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 2L19 2C20.65685 2 22 3.34315 22 5L22 11C22 12.65685 20.65685 14 19 14L5 14C3.34315 14 2 12.65685 2 11L2 5C2 3.34315 3.34315 2 5 2Z");
  stroke: none;
}

:global(.yacyzm0cg) {
  d: path("M5 3L19 3C20.10457 3 21 3.89543 21 5L21 11C21 12.10457 20.10457 13 19 13L5 13C3.89543 13 3 12.10457 3 11L3 5C3 3.89543 3.89543 3 5 3ZM5 17H19M7 21H17");
}

</style>
