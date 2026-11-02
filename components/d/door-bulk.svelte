<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="z0kktyjuc"/><path class="fyemarmgs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:door-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.fyemarmgs) {
  d: path("M14 11h.01a1 1 0 0 1 0 2H14a1 1 0 0 1 0-2m7 9a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

:global(.z0kktyjuc) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 22H6a1 1 0 0 1-1-1V5a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v16a1 1 0 0 1-1 1");
}

</style>
