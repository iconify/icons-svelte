<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixiqeioib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:roofing" {...props}></Icon>
<style>
:global(.ixiqeioib) {
  fill: currentColor;
  d: path("M9 20v-6h6v6zm-6.8-7L1 11.4L12 3l4 3.05V4h3v4.35l4 3.05l-1.2 1.6L12 5.525z");
}

</style>
