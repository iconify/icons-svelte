<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tj3yo8bxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-down-up-bulk-round" {...props}></Icon>
<style>
:global(.tj3yo8bxf) {
  fill: currentColor;
  d: path("m7.293 19.707l-4-4a.999.999 0 1 1 1.414-1.414L7 16.586V5a1 1 0 0 1 2 0v11.586l2.293-2.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0M17 7.414V19a1 1 0 0 1-2 0V7.414l-2.293 2.293a.999.999 0 1 1-1.414-1.414l4-4a1 1 0 0 1 1.414 0l4 4a.999.999 0 1 1-1.414 1.414Z");
}

</style>
