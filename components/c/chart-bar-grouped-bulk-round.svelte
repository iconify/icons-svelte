<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3g2ivbey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-bar-grouped-bulk-round" {...props}></Icon>
<style>
:global(.w3g2ivbey) {
  fill: currentColor;
  d: path("M9 21a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm11 0V7a1 1 0 0 1 2 0v14a1 1 0 0 1-2 0M4 21a1 1 0 0 1-2 0V11a1 1 0 0 1 2 0Zm13 0a1 1 0 0 1-2 0v-6a1 1 0 0 1 2 0Z");
}

</style>
