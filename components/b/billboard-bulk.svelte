<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c1b__8bbs"/><path class="nw82umbye"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:billboard-bulk" {...props}></Icon>
<style>
:global(.c1b__8bbs) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.nw82umbye) {
  d: path("M7 6h10a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2m0 4h6a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2M6 21v-6a1 1 0 0 1 2 0v6a1 1 0 0 1-2 0m10 0v-6a1 1 0 0 1 2 0v6a1 1 0 0 1-2 0");
}

</style>
