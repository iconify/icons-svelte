<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bpp7y5g_r"/><path class="bb50odo-i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:nfc-bulk-sharp" {...props}></Icon>
<style>
:global(.bb50odo-i) {
  d: path("M7 8a1.002 1.002 0 0 1 1.707-.707L15 13.586V3a1 1 0 0 1 2 0v13a1.002 1.002 0 0 1-1.707.707L9 10.414V21a1 1 0 0 1-2 0Z");
}

:global(.bpp7y5g_r) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

</style>
