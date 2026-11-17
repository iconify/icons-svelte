<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ed7z7vbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:air-conditioner-off-fill-round" {...props}></Icon>
<style>
:global(.ed7z7vbhd) {
  fill: currentColor;
  d: path("M7 2h10a5 5 0 0 1 0 10H7A5 5 0 0 1 7 2m0 5a1 1 0 0 0 0 2h10a1 1 0 0 0 0-2Z");
}

</style>
