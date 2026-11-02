<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h0a7fgn5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chevron-right-large-bulk" {...props}></Icon>
<style>
:global(.h0a7fgn5x) {
  fill: currentColor;
  d: path("M13.586 12L8.293 6.707a.999.999 0 1 1 1.414-1.414l6 6a1 1 0 0 1 0 1.414l-6 6a.999.999 0 1 1-1.414-1.414Z");
}

</style>
