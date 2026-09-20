<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ndej6767w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:featured-video-sharp" {...props}></Icon>
<style>
:global(.ndej6767w) {
  fill: currentColor;
  d: path("M5.5 13.5h8v-6h-8zM3 19V5h18v14z");
}

</style>
