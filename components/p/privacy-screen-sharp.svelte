<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xiaypfbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:privacy-screen-sharp" {...props}></Icon>
<style>
:global(.xiaypfbxd) {
  fill: currentColor;
  d: path("M2 11.6L9.6 4H2Zm0 7L16.575 4H12.4L2 14.425ZM3.4 20H22V4h-2.6Z");
}

</style>
