<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tuoq_xbai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:check-large-bulk" {...props}></Icon>
<style>
:global(.tuoq_xbai) {
  fill: currentColor;
  d: path("M9 16.586L20.293 5.293a.999.999 0 1 1 1.414 1.414l-12 12a1 1 0 0 1-1.414 0l-6-6a.999.999 0 1 1 1.414-1.414Z");
}

</style>
