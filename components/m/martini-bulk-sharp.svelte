<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dwsfs8bks"/><path class="iv0w9bbpt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:martini-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.dwsfs8bks) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 2h16a1.002 1.002 0 0 1 .707 1.707l-8 8a1 1 0 0 1-1.414 0l-8-8A1 1 0 0 1 4 2");
}

:global(.iv0w9bbpt) {
  d: path("M7 5h10a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2m1 17a1 1 0 0 1 0-2h3v-9a1 1 0 0 1 2 0v9h3a1 1 0 0 1 0 2Z");
}

</style>
