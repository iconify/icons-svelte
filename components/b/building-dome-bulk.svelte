<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fw9aw0bgg"/><path class="g_y_nhbrd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:building-dome-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.fw9aw0bgg) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 10H5a1 1 0 0 1-1-1a6.2 6.2 0 0 1 .653-2.778a7 7 0 0 1 1.746-2.224C7.945 2.673 9.975 2 12 2s4.055.673 5.601 1.998a7 7 0 0 1 1.746 2.224c.431.863.654 1.814.653 2.778a1 1 0 0 1-1 1");
}

:global(.g_y_nhbrd) {
  d: path("M3 10a1 1 0 0 1 0-2h18a1 1 0 0 1 0 2Zm4 3v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0m4 0v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0m4 0v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0m4 0v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0M3 20h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

</style>
