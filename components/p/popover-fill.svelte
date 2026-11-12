<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iuklytbur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:popover-fill" {...props}></Icon>
<style>
:global(.iuklytbur) {
  fill: currentColor;
  d: path("M5 6h3.5l2.7-3.6a1 1 0 0 1 1.6 0L15.5 6H19a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3m12 5H7a1 1 0 0 0 0 2h10a1 1 0 0 0 0-2M7 15a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2Z");
}

</style>
