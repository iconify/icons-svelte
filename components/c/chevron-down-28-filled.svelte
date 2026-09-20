<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="pa6ncgweb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:chevron-down-28-filled" {...props}></Icon>
<style>
:global(.pa6ncgweb) {
  fill: currentColor;
  d: path("M4.293 9.293a1 1 0 0 1 1.414 0L14 17.586l8.293-8.293a1 1 0 1 1 1.414 1.414l-9 9a1 1 0 0 1-1.414 0l-9-9a1 1 0 0 1 0-1.414");
}

</style>
