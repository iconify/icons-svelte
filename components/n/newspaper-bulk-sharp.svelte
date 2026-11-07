<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="q-66sabiu"/><path class="g6qhq3bhs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:newspaper-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.g6qhq3bhs) {
  d: path("M8 8v12a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0m4-1h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2m0 4h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2m0 4h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2");
}

:global(.q-66sabiu) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 3h14a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1h3V4a1 1 0 0 1 1-1");
}

</style>
