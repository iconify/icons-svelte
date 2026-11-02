<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pf-scx21l"/><path class="cs0u5dlyv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bed-bulk-sharp" {...props}></Icon>
<style>
:global(.cs0u5dlyv) {
  d: path("M4 8h17a1 1 0 0 1 1 1v10a1 1 0 0 1-2 0v-9H8v6a1 1 0 0 1-2 0v-6H4v9a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0Z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.pf-scx21l) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 9a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v7a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

</style>
