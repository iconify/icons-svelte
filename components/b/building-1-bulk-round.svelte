<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bc0ft1biw"/><path class="cs38jmh7x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:building-1-bulk-round" {...props}></Icon>
<style>
:global(.bc0ft1biw) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 21H5a1 1 0 0 1-1-1V7a4 4 0 0 1 4-4h1a4 4 0 0 1 4 4v13a1 1 0 0 1-1 1");
}

:global(.cs38jmh7x) {
  d: path("M8 19v-4.078a5 5 0 0 1 1.876-3.904l1-.8a5 5 0 0 1 6.248 0l1 .8A4.98 4.98 0 0 1 20 14.922V19h1a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm2 0h8v-4.078a2.99 2.99 0 0 0-1.126-2.342l-1-.8a3 3 0 0 0-3.748 0l-1 .8A3 3 0 0 0 10 14.922Z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

</style>
