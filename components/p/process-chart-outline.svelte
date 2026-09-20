<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxmm2orvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:process-chart-outline" {...props}></Icon>
<style>
:global(.uxmm2orvf) {
  fill: currentColor;
  d: path("m3.3 18.45l-1.8-.9l6-12l1.8.9zm6.6 0l-1.8-.9l6-12l1.8.9zm6.6 0l-1.8-.9l6-12l1.8.9z");
}

</style>
