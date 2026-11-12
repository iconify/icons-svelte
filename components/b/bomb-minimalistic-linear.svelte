<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="uac092bgj"/><path class="m99yuxjsm"/><path class="zsnush0dj"/><path class="wlfsgdzfw"/><path class="n04922jxw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bomb-minimalistic-linear" {...props}></Icon>
<style>
:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m99yuxjsm) {
  d: path("M17 7L15 9");
}

:global(.n04922jxw) {
  d: path("M19 5L20 4");
}

:global(.uac092bgj) {
  cx: 9.5px;
  cy: 14.5px;
  r: 7.5px;
}

:global(.wlfsgdzfw) {
  d: path("M16 3.5L16.5 4.5");
}

:global(.zsnush0dj) {
  d: path("M19.5 7.5L20.5 8");
}

</style>
