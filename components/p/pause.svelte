<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxk4d9y5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:pause" {...props}></Icon>
<style>
:global(.dxk4d9y5y) {
  fill: currentColor;
  d: path("M6 19h4V5H6zm8-14v14h4V5z");
}

</style>
