<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lo2spemcq"/><path class="ughdv9bzg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:microphone-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.lo2spemcq) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 6a4 4 0 0 1 8 0v5a4 4 0 0 1-8 0Z");
}

:global(.ughdv9bzg) {
  d: path("M6 10v1a6 6 0 1 0 12 0v-1a1 1 0 0 1 2 0v1a8.006 8.006 0 0 1-7 7.939V21a1 1 0 0 1-2 0v-2.061A8.006 8.006 0 0 1 4 11v-1a1 1 0 0 1 2 0");
}

</style>
