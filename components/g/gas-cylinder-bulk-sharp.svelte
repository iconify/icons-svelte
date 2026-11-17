<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qgtn9tw2q"/><path class="zesefc_er"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:gas-cylinder-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.qgtn9tw2q) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 2a1 1 0 0 1 1 1v3.099A5.01 5.01 0 0 1 21 11v8a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1v-8a5.01 5.01 0 0 1 4-4.901V3a1 1 0 0 1 1-1ZM9 4v2h6V4Z");
}

:global(.zesefc_er) {
  d: path("M7 3a1 1 0 0 1 1-1h8a1 1 0 0 1 1 1v4a1 1 0 0 1-2 0V4H9v3a1 1 0 0 1-2 0Zm13 9a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2ZM9 20h6v-1a1 1 0 0 1 2 0v2a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1v-2a1 1 0 0 1 2 0Z");
}

</style>
