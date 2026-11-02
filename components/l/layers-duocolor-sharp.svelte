<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hmevflb0n"/><path class="y06mwtt6k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:layers-duocolor-sharp" {...props}></Icon>
<style>
:global(.hmevflb0n) {
  stroke-opacity: 0.4;
  d: path("m4 12l8 4l8-4M4 16l8 4l8-4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.y06mwtt6k) {
  d: path("m8 6l4-2l8 4l-8 4l-8-4z");
}

</style>
