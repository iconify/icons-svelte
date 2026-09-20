<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a4kopghvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:divider-short-20-filled" {...props}></Icon>
<style>
:global(.a4kopghvc) {
  fill: currentColor;
  d: path("M9.75 3a.75.75 0 0 1 .75.75v12.5a.75.75 0 0 1-1.5 0V3.75A.75.75 0 0 1 9.75 3");
}

</style>
