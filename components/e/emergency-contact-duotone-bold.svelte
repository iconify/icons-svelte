<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="w-icpcn9a"/><path class="hh3gqccwb"/><path class="e5gef0b8q"/><path class="eb5zxsbop"/><path class="mz4c5lb-h"/><path class="meft4rjfc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:emergency-contact-duotone-bold" {...props}></Icon>
<style>
:global(.e5gef0b8q) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13.5 11a3.5 3.5 0 0 1 7 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.eb5zxsbop) {
  d: path("M4 5a2 2 0 0 1 4 0v3a2 2 0 0 1 -4 0Zm0 3c0 6 6 12 12 12m0 0a2 2 0 0 0 4 0v-3a2 2 0 0 0 -4 0Z");
}

:global(.hh3gqccwb) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 5a2 2 0 0 1 4 0v3a2 2 0 0 1 -4 0Zm0 3c0 6 6 12 12 12m0 0a2 2 0 0 0 4 0v-3a2 2 0 0 0 -4 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.meft4rjfc) {
  d: path("M13.5 11a3.5 3.5 0 0 1 7 0");
}

:global(.mz4c5lb-h) {
  d: path("M15 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.w-icpcn9a) {
  fill: currentColor;
  d: path("M15 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
