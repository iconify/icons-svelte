<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wb73dcc1r"/><path class="n36qpwqix"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mars-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.n36qpwqix) {
  d: path("M18.586 4H15a1 1 0 0 1 0-2h6a1 1 0 0 1 1 1v6a1 1 0 0 1-2 0V5.414l-7.293 7.293a.999.999 0 1 1-1.414-1.414Z");
}

:global(.wb73dcc1r) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 16a6 6 0 1 1 12 0a6 6 0 0 1-12 0");
}

</style>
