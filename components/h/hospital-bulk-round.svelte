<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uuittcc3u"/><path class="h9--ptifm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hospital-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.h9--ptifm) {
  d: path("M13 7v2h2a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2H9a1 1 0 0 1 0-2h2V7a1 1 0 0 1 2 0m8 15H3a1 1 0 0 1 0-2h6v-1a3 3 0 1 1 6 0v1h6a1 1 0 0 1 0 2m-8-2v-1a1 1 0 0 0-2 0v1Z");
}

:global(.uuittcc3u) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 22H5a1 1 0 0 1-1-1V7a5 5 0 0 1 5-5h6a5 5 0 0 1 5 5v14a1 1 0 0 1-1 1");
}

</style>
