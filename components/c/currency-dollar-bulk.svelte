<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vd0-fwbnp"/><path class="tf82ozbow"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:currency-dollar-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.tf82ozbow) {
  d: path("M14 6h-4a2 2 0 0 0-2 2v1a2 2 0 0 0 2 2h4a4 4 0 0 1 4 4v1a4 4 0 0 1-4 4h-4a3.98 3.98 0 0 1-2.828-1.172A3.98 3.98 0 0 1 6 16a1 1 0 0 1 2 0a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2v-1a2 2 0 0 0-2-2h-4a4 4 0 0 1-4-4V8a4 4 0 0 1 4-4h4c1.064 0 2.078.418 2.828 1.172A3.98 3.98 0 0 1 18 8a1 1 0 0 1-2 0a2 2 0 0 0-2-2");
}

:global(.vd0-fwbnp) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 5a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm0 16a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Z");
}

</style>
