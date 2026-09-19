<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="erkqwpm1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-flash-on" {...props}></Icon>
<style>
:global(.erkqwpm1w) {
  fill: currentColor;
  d: path("M7 2v11h3v9l7-12h-4l3-8z");
}

</style>
