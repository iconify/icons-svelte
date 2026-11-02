<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0_57np6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-right-large-bulk-round" {...props}></Icon>
<style>
:global(.s0_57np6e) {
  fill: currentColor;
  d: path("M18.586 13H3a1 1 0 0 1 0-2h15.586l-4.293-4.293a.999.999 0 1 1 1.414-1.414l6 6a1 1 0 0 1 0 1.414l-6 6a.999.999 0 1 1-1.414-1.414Z");
}

</style>
