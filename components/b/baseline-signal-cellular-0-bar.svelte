<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-nf5tb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-signal-cellular-0-bar" {...props}></Icon>
<style>
:global(.g-nf5tb5r) {
  fill: currentColor;
  d: path("M20 6.83V20H6.83zM22 2L2 22h20z");
}

</style>
