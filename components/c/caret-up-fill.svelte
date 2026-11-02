<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="osy3mqf7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:caret-up-fill" {...props}></Icon>
<style>
:global(.osy3mqf7d) {
  fill: currentColor;
  d: path("M11.293 9.293a1 1 0 0 1 1.414 0l4 4A1 1 0 0 1 16 15H8a1.002 1.002 0 0 1-.707-1.707Z");
}

</style>
