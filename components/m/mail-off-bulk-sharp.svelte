<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i3b8yi-zo"/><path class="k2mchmb9u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mail-off-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.i3b8yi-zo) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m4 4l16 16H3a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1Zm18 13.757L8.243 4H21a1 1 0 0 1 1 1Z");
}

:global(.k2mchmb9u) {
  d: path("m2.707 1.293l20 20a.999.999 0 1 1-1.414 1.414l-20-20a.999.999 0 1 1 1.414-1.414m13.121 10.293l-1.414-1.414l.867-.867l.012-.012l5-5a.999.999 0 1 1 1.414 1.414l-5 5l-.012.012Z");
}

</style>
