<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqf5aabfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:area-chart-outline-sharp" {...props}></Icon>
<style>
:global(.jqf5aabfq) {
  fill: currentColor;
  d: path("M3 20V7l4 3l5-7l5 4h4v13zm5-3l4-5.5l7 5.45V9h-2.7l-3.9-3.125l-4.95 6.95L5 11v3.6z");
}

</style>
