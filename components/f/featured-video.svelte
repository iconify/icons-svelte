<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpae73bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:featured-video" {...props}></Icon>
<style>
:global(.cpae73bqt) {
  fill: currentColor;
  d: path("M21 3H3c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h18c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m-9 9H3V5h9z");
}

</style>
