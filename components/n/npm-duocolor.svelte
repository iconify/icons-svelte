<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o-zxycb7m"/><path class="kj6daq0ea"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:npm-duocolor" {...props}></Icon>
<style>
:global(.kj6daq0ea) {
  d: path("M14 21V10");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o-zxycb7m) {
  stroke-opacity: 0.4;
  d: path("M3 3h18v18H3Z");
}

</style>
