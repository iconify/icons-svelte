<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ht51h8bgs"/><path class="cmm2qabry"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:dialpad-bulk-sharp" {...props}></Icon>
<style>
:global(.cmm2qabry) {
  d: path("M6.01 3a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Zm6 0a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Zm6 0a1 1 0 0 1 0 2H18a1 1 0 0 1 0-2Zm-12 5a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Zm6 0a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Zm6 0a1 1 0 0 1 0 2H18a1 1 0 0 1 0-2Zm-12 5a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Zm6 0a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Zm6 0a1 1 0 0 1 0 2H18a1 1 0 0 1 0-2Z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.ht51h8bgs) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 18h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

</style>
