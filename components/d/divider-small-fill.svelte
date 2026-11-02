<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="er3-szkyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:divider-small-fill" {...props}></Icon>
<style>
:global(.er3-szkyi) {
  fill: currentColor;
  d: path("M13 9v6a1 1 0 0 1-2 0V9a1 1 0 0 1 2 0");
}

</style>
