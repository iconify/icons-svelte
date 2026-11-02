<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lxra9ac4k"/><path class="n4vwsnj3k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:align-top-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.lxra9ac4k) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 8a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Zm10 0a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1h-6a1 1 0 0 1-1-1Z");
}

:global(.n4vwsnj3k) {
  d: path("M3 3h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

</style>
