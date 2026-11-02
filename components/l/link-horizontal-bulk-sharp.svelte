<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ls6shcckx"/><path class="qjmi1nwvd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:link-horizontal-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.ls6shcckx) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 11h8a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2");
}

:global(.qjmi1nwvd) {
  d: path("M7 9a3 3 0 1 0 0 6h2a1 1 0 0 1 0 2H7A5 5 0 0 1 7 7h2a1 1 0 0 1 0 2Zm10-2a5 5 0 0 1 0 10h-2a1 1 0 0 1 0-2h2a3 3 0 1 0 0-6h-2a1 1 0 0 1 0-2Z");
}

</style>
