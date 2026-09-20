<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="pdxeg-bwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:diamond-28-filled" {...props}></Icon>
<style>
:global(.pdxeg-bwl) {
  fill: currentColor;
  d: path("M11.35 2.099a3.75 3.75 0 0 1 5.303 0l9.25 9.251a3.75 3.75 0 0 1 0 5.303l-9.25 9.25a3.75 3.75 0 0 1-5.304 0l-9.25-9.25a3.75 3.75 0 0 1 0-5.303z");
}

</style>
