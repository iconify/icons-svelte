<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g5wnm1b8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-rectangle" {...props}></Icon>
<style>
:global(.g5wnm1b8d) {
  fill: currentColor;
  d: path("M2 4v16h20V4zm18 14H4V6h16z");
}

</style>
