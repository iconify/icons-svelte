<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1edizbwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:re-order-vertical-24-filled" {...props}></Icon>
<style>
:global(.g1edizbwy) {
  fill: currentColor;
  d: path("M13 21V3a1 1 0 0 1 1.993-.117L15 3v18a1 1 0 0 1-1.993.117zm-4 0V3a1 1 0 0 1 1.993-.117L11 3v18a1 1 0 0 1-1.993.117z");
}

</style>
