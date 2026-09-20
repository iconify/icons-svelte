<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ti4xdpbxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:chevron-left-20-regular" {...props}></Icon>
<style>
:global(.ti4xdpbxp) {
  fill: currentColor;
  d: path("M12.353 15.854a.5.5 0 0 1-.707.001L6.162 10.39a.55.55 0 0 1 0-.78l5.484-5.464a.5.5 0 1 1 .706.708L7.188 10l5.164 5.147a.5.5 0 0 1 .001.707");
}

</style>
