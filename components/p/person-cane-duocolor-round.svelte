<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rq611mfwl"/><path class="nr3zanbnw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:person-cane-duocolor-round" {...props}></Icon>
<style>
:global(.nr3zanbnw) {
  d: path("M7 4a1 1 0 1 0 2 0a1 1 0 0 0-2 0m1 4v6m-3 7l3-7l3 7M8 9l5 3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rq611mfwl) {
  stroke-opacity: 0.4;
  d: path("m13 12l6 9");
}

</style>
