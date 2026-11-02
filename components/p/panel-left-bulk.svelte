<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nu45ocbzb"/><path class="rgnjs8brm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:panel-left-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.nu45ocbzb) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 3a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3Z");
}

:global(.rgnjs8brm) {
  d: path("M10 4v16a1 1 0 0 1-2 0V4a1 1 0 0 1 2 0");
}

</style>
