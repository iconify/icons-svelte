<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ggst7bcrg"/><path class="iag78lcrt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:gallery-vertical-start-fill" {...props}></Icon>
<style>
:global(.ggst7bcrg) {
  fill: currentColor;
  d: path("M5 2L19 2C20.65685 2 22 3.34315 22 5L22 11C22 12.65685 20.65685 14 19 14L5 14C3.34315 14 2 12.65685 2 11L2 5C2 3.34315 3.34315 2 5 2Z");
  stroke: none;
}

:global(.iag78lcrt) {
  d: path("M5 17H19M7 21H17");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
