<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sjr9x5bay"/><path class="hn13l6b8j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:battery-low-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.hn13l6b8j) {
  d: path("M7 10v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0m15 0v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0");
}

:global(.sjr9x5bay) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 10a4 4 0 0 1 4-4h9a4 4 0 0 1 4 4v4a4 4 0 0 1-4 4H6a4 4 0 0 1-4-4Z");
}

</style>
