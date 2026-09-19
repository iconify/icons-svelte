<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uyyeshb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-vertical-shades" {...props}></Icon>
<style>
:global(.uyyeshb6v) {
  fill: currentColor;
  d: path("M20 19V3H4v16H2v2h20v-2zM14 5v14h-4V5zM6 5h2v14H6zm10 14V5h2v14z");
}

</style>
