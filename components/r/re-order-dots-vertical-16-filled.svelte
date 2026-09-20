<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bel7igkbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:re-order-dots-vertical-16-filled" {...props}></Icon>
<style>
:global(.bel7igkbd) {
  fill: currentColor;
  d: path("M5.5 5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3m0 4.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3m1.5 3a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0M10.5 5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3M12 8a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m-1.5 6a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3");
}

</style>
