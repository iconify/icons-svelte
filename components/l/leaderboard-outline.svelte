<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yi2sg6bfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:leaderboard-outline" {...props}></Icon>
<style>
:global(.yi2sg6bfk) {
  fill: currentColor;
  d: path("M4 19h4.673v-8H4zm5.673 0h4.654V5H9.673zm5.654 0H20v-6h-4.673zM3 20V10h5.673V4h6.654v8H21v8z");
}

</style>
