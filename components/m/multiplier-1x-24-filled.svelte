<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwdtzlbkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:multiplier-1x-24-filled" {...props}></Icon>
<style>
:global(.gwdtzlbkt) {
  fill: currentColor;
  d: path("M10 7.902a1 1 0 0 0-1.854-.52l-.073.12c-.403.667-.842 1.394-2.087 2.14a1 1 0 0 0 1.029 1.716A8.5 8.5 0 0 0 8 10.672v5.329a1 1 0 1 0 2 0zm3.707 4.392a1 1 0 1 0-1.414 1.414l.793.793l-.793.793a1 1 0 0 0 1.414 1.414l.793-.793l.793.793a1 1 0 1 0 1.414-1.414l-.793-.793l.793-.793a1 1 0 0 0-1.414-1.414l-.793.793z");
}

</style>
