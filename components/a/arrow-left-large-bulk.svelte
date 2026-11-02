<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnfar-bps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-left-large-bulk" {...props}></Icon>
<style>
:global(.vnfar-bps) {
  fill: currentColor;
  d: path("M5.414 11H21a1 1 0 0 1 0 2H5.414l4.293 4.293a.999.999 0 1 1-1.414 1.414l-6-6a1 1 0 0 1 0-1.414l6-6a.999.999 0 1 1 1.414 1.414Z");
}

</style>
