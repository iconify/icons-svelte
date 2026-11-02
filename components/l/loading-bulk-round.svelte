<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u2c5tobtk"/><path class="nacd-ebdq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:loading-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.nacd-ebdq) {
  d: path("M16.158 9.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m-12 4a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558");
}

:global(.u2c5tobtk) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.158 11.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558");
}

</style>
