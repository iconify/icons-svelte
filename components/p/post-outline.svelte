<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ad0ps083t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:post-outline" {...props}></Icon>
<style>
:global(.ad0ps083t) {
  fill: currentColor;
  d: path("M3 21V3h18v18zm15-4H6v1.5h12zM6 15.5h12V14H6zM6 12h12V6H6zm0 5v1.5zm0-1.5V14zM6 12V6zm0 2v-2zm0 3v-1.5z");
}

</style>
