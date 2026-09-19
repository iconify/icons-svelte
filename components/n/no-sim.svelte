<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="llj9s3bkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:no-sim" {...props}></Icon>
<style>
:global(.llj9s3bkp) {
  fill: currentColor;
  d: path("M18.99 5c0-1.1-.89-2-1.99-2h-7L7.66 5.34L19 16.68zM3.65 3.88L2.38 5.15L5 7.77V19c0 1.1.9 2 2 2h10.01c.35 0 .67-.1.96-.26l1.88 1.88l1.27-1.27z");
}

</style>
