<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nyzdfrksg"/><path class="sob878tac"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:note-pause-corner-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.nyzdfrksg) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 3h16a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H9v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1");
}

:global(.sob878tac) {
  d: path("M16 21a1 1 0 0 1-2 0v-8a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0v-8a1 1 0 0 1 2 0Z");
}

</style>
