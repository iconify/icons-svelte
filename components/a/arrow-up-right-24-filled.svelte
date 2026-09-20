<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2poqbbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-up-right-24-filled" {...props}></Icon>
<style>
:global(.n2poqbbxd) {
  fill: currentColor;
  d: path("M11 3a1 1 0 1 0 0 2h6.586L3.293 19.293a1 1 0 1 0 1.414 1.414L19 6.414V13a1 1 0 1 0 2 0V4a1 1 0 0 0-1-1z");
}

</style>
