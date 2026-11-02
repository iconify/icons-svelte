<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x6t4l0b5i"/><path class="tt7zpdcyl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bath-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.tt7zpdcyl) {
  d: path("M3 13a1 1 0 0 1 0-2h1V6a3 3 0 1 1 6 0a1 1 0 0 1-2 0a1.001 1.001 0 0 0-2 0v5h15a1 1 0 0 1 0 2Zm6 7a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Zm8 0a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Z");
}

:global(.x6t4l0b5i) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 11h14a1 1 0 0 1 1 1v4a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3v-4a1 1 0 0 1 1-1");
}

</style>
