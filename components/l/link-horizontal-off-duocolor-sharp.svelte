<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yslnx84sq"/><path class="w23wm3bzq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:link-horizontal-off-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.w23wm3bzq) {
  d: path("M8 8H7a4 4 0 1 0 0 8h2m6-8h2a4 4 0 0 1 4 4c0 .85-.549 1.352-1 2");
}

:global(.yslnx84sq) {
  stroke-opacity: 0.4;
  d: path("M8 12h4M2 2l20 20");
}

</style>
