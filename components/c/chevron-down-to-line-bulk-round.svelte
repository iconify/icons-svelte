<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xe3-hr2np"/><path class="e59aw4bgg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chevron-down-to-line-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.e59aw4bgg) {
  d: path("m12 11.586l5.293-5.293a.999.999 0 1 1 1.414 1.414l-6 6a1 1 0 0 1-1.414 0l-6-6a.999.999 0 1 1 1.414-1.414Z");
}

:global(.xe3-hr2np) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 16h12a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2");
}

</style>
