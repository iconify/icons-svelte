<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yak33lb9w"/><path class="z9ittvbis"/><path class="gr0pfvalr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:daylight-hours-outline-regular" {...props}></Icon>
<style>
:global(.gr0pfvalr) {
  d: path("M9 10a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.yak33lb9w) {
  d: path("M3 19a9 9 0 0 1 18 0");
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
