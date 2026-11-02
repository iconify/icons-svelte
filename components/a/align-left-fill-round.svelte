<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_appmbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:align-left-fill-round" {...props}></Icon>
<style>
:global(.h_appmbcd) {
  fill: currentColor;
  d: path("M5 21a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm6-18h6a4 4 0 0 1 0 8h-6a4 4 0 0 1 0-8m0 10h2a4 4 0 0 1 0 8h-2a4 4 0 0 1 0-8");
}

</style>
