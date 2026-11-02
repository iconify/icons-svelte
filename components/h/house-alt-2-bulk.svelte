<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ls3_3kbof"/><path class="gt71-xrst"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-alt-2-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.gt71-xrst) {
  d: path("M3 21a1 1 0 0 1 0-2h6v-3a3 3 0 1 1 6 0v3h6a1 1 0 0 1 0 2Zm10-2v-3a1 1 0 0 0-2 0v3Z");
}

:global(.ls3_3kbof) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 12c0-1.039.578-1.992 1.293-2.707l5-5a2.414 2.414 0 0 1 3.414 0l5 5C19.422 10.008 20 10.961 20 12v8a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1Zm10 4a2 2 0 1 0-4 0v4h4Z");
}

</style>
