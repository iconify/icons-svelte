<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a2axkab4k"/><path class="rsywueblk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-warning-bulk-round" {...props}></Icon>
<style>
:global(.a2axkab4k) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.707 3.293L12.414 5H17a5 5 0 0 1 5 5v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21H7a5 5 0 0 1-5-5V6a3 3 0 0 1 3-3h5c.265 0 .52.105.707.293");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.rsywueblk) {
  d: path("M13 13a1 1 0 0 1-2 0v-3a1 1 0 0 1 2 0Zm-.99 2a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Z");
}

</style>
