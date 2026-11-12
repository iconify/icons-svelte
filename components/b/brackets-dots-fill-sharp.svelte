<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktml00bdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:brackets-dots-fill-sharp" {...props}></Icon>
<style>
:global(.ktml00bdt) {
  fill: currentColor;
  d: path("M6 4H4v16h2a1 1 0 0 1 0 2H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1h3a1 1 0 0 1 0 2m12-2h3a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1h-3a1 1 0 0 1 0-2h2V4h-2a1 1 0 0 1 0-2M9 5h.01a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2m6 0h.01a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2m-6 6h.01a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2m6 0h.01a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2m-6 6h.01a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2m6 0h.01a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2");
}

</style>
