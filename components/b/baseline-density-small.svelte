<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bv4_abj-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-density-small" {...props}></Icon>
<style>
:global(.bv4_abj-g) {
  fill: currentColor;
  d: path("M3 2h18v2H3zm0 18h18v2H3zm0-6h18v2H3zm0-6h18v2H3z");
}

</style>
