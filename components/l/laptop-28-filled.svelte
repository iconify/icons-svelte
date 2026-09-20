<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="l0xwc5npf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:laptop-28-filled" {...props}></Icon>
<style>
:global(.l0xwc5npf) {
  fill: currentColor;
  d: path("M4.004 7.75A2.75 2.75 0 0 1 6.754 5h14.5a2.75 2.75 0 0 1 2.75 2.75v8.5a2.75 2.75 0 0 1-2.75 2.75h-14.5a2.75 2.75 0 0 1-2.75-2.75zm-2 13.5a.75.75 0 0 1 .75-.75H25.25a.75.75 0 0 1 0 1.5H2.755a.75.75 0 0 1-.75-.75");
}

</style>
