<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="z5gvel7ot"/><path class="xedu8iwma"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:copy-plus-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.xedu8iwma) {
  d: path("M15 11v2a1 1 0 0 1-2 0v-2h-2a1 1 0 0 1 0-2h2V7a1 1 0 0 1 2 0v2h2a1 1 0 0 1 0 2ZM4 19a1 1 0 0 0 1 1h10a1 1 0 0 1 0 2H5a3 3 0 0 1-3-3V9a1 1 0 0 1 2 0Z");
}

:global(.z5gvel7ot) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 5a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3Z");
}

</style>
