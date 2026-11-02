<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gl16ndboh"/><path class="iiel43b5s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:path-duocolor" {...props}></Icon>
<style>
:global(.gl16ndboh) {
  stroke-opacity: 0.4;
  d: path("M3 18a3 3 0 1 0 6 0a3 3 0 0 0-6 0M15 6a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

:global(.iiel43b5s) {
  d: path("M8.121 15.879L15.88 8.12");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
