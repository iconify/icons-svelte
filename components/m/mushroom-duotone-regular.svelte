<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mft5sm3ri"/><path class="e4rbzsbiw"/><path class="sg8usjbiz"/><path class="u2vvzw7_k"/><path class="wuk2mlziz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mushroom-duotone-regular" {...props}></Icon>
<style>
:global(.e4rbzsbiw) {
  d: path("M3 11a9 9 0 0 1 18 0Z");
}

:global(.mft5sm3ri) {
  fill: currentColor;
  d: path("M3 11a9 9 0 0 1 18 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sg8usjbiz) {
  d: path("M9 13v6");
}

:global(.u2vvzw7_k) {
  d: path("M15 13v6");
}

:global(.wuk2mlziz) {
  d: path("M7 19h10");
}

</style>
