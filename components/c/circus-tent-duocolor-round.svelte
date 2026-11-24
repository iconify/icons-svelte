<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h3mdmwu4o"/><path class="px0wev7nk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circus-tent-duocolor-round" {...props}></Icon>
<style>
:global(.h3mdmwu4o) {
  stroke-opacity: 0.4;
  d: path("M12 7V3l3 1l-3 1M8 21l4-4l4 4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.px0wev7nk) {
  d: path("M4 21V11c0-2 6-2 8-4c2 2 8 2 8 4v10M3 21h5m8 0h5M4 11a2 2 0 1 0 4 0a2 2 0 1 0 4 0a2 2 0 1 0 4 0a2 2 0 1 0 4 0");
}

</style>
