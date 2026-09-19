<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bymtx97uw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:explicit" {...props}></Icon>
<style>
:global(.bymtx97uw) {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m-4 6h-4v2h4v2h-4v2h4v2H9V7h6z");
}

</style>
