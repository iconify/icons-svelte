<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l5q2_7b2j"/><path class="v6pg86b0d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:git-fork-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.l5q2_7b2j) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6a3 3 0 1 1 6 0a3 3 0 0 1-6 0m14 0a3 3 0 1 1 6 0a3 3 0 0 1-6 0M9 18a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

:global(.v6pg86b0d) {
  d: path("M4 8a1 1 0 0 1 2 0v3h12V8a1 1 0 0 1 2 0v4a1 1 0 0 1-1 1h-6v3a1 1 0 0 1-2 0v-3H5a1 1 0 0 1-1-1Z");
}

</style>
