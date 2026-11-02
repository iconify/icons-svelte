<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xrvxr8byk"/><path class="x9ahn40kq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:broadcast-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.x9ahn40kq) {
  d: path("M12 12h.01");
}

:global(.xrvxr8byk) {
  stroke-opacity: 0.4;
  d: path("M15 9a4.243 4.243 0 0 1 0 6m3-9a8.485 8.485 0 0 1 0 12m-9-3a4.243 4.243 0 0 1 0-6m-3 9A8.485 8.485 0 0 1 6 6");
}

</style>
