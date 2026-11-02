<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhqsqi7qs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:equal-fill" {...props}></Icon>
<style>
:global(.bhqsqi7qs) {
  fill: currentColor;
  d: path("M18 8a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Zm0 6a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Z");
}

</style>
