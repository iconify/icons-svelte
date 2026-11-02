<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ldmad_xfq"/><path class="hdk9sqbka"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-right-to-line-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.hdk9sqbka) {
  d: path("M13.586 13H4a1 1 0 0 1 0-2h9.586l-2.293-2.293a.999.999 0 1 1 1.414-1.414l4 4a1 1 0 0 1 0 1.414l-4 4a.999.999 0 1 1-1.414-1.414Z");
}

:global(.ldmad_xfq) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 6v12a1 1 0 0 1-2 0V6a1 1 0 0 1 2 0");
}

</style>
