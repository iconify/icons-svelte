<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gs1sv8b-u"/><path class="cy2w0abow"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:import-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.cy2w0abow) {
  d: path("M4 9v8a3 3 0 0 0 3 3h10a3 3 0 0 0 3-3V9a1 1 0 0 0-1-1a1 1 0 0 1 0-2a3 3 0 0 1 3 3v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5V9a3 3 0 0 1 3-3a1 1 0 0 1 0 2a1 1 0 0 0-1 1");
}

:global(.gs1sv8b-u) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m11.292 15.707l-2.999-3a.999.999 0 1 1 1.414-1.414L11 12.586V3a1 1 0 0 1 2 0v9.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0Z");
}

</style>
