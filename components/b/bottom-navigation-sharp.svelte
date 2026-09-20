<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eptikw0xo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:bottom-navigation-sharp" {...props}></Icon>
<style>
:global(.eptikw0xo) {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-6h14V5H5z");
}

</style>
