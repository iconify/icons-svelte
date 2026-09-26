<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rlqigwbqk"/><path class="a9ur9fbnp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-top-dashed-duotone" {...props}></Icon>
<style>
:global(.a9ur9fbnp) {
  d: path("M3 18C3 19.6569 4.34315 21 6 21M18 21C19.6569 21 21 19.6569 21 18M3 13V14M21 13V14M10.5 21H13.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rlqigwbqk) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 2L18 2C20.2091 2 22 3.7909 22 6L22 9C22 9.5523 21.5523 10 21 10L3 10C2.4477 10 2 9.5523 2 9L2 6C2 3.7909 3.7909 2 6 2Z");
  stroke: none;
}

</style>
