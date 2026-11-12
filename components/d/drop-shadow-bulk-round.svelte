<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bicvrsrad"/><path class="ahukaab0n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:drop-shadow-bulk-round" {...props}></Icon>
<style>
:global(.ahukaab0n) {
  d: path("M7 20h10a3.004 3.004 0 0 0 3-3V7a1 1 0 0 1 2 0v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a1 1 0 0 1 0-2");
}

:global(.bicvrsrad) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 7a5 5 0 0 1 5-5h4a5 5 0 0 1 5 5v4a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5Z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

</style>
