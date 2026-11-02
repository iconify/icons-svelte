<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oe5303d4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:columns-fill-round" {...props}></Icon>
<style>
:global(.oe5303d4d) {
  fill: currentColor;
  d: path("M11 7v10a4 4 0 0 1-8 0V7a4 4 0 0 1 8 0m10 0v10a4 4 0 0 1-8 0V7a4 4 0 0 1 8 0");
}

</style>
