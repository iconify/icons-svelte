<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vzo4jk9yh"/><path class="eevg6pb8h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:plug-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.eevg6pb8h) {
  d: path("M10 7a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm6-4v4a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0m-3 18a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0Z");
}

:global(.vzo4jk9yh) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 11a5 5 0 0 1 5-5h4a5 5 0 0 1 5 5v2a5 5 0 0 1-5 5h-4a5 5 0 0 1-5-5Z");
}

</style>
