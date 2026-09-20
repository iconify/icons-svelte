<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="ly0gbcblz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-up-right-28-filled" {...props}></Icon>
<style>
:global(.ly0gbcblz) {
  fill: currentColor;
  d: path("M3.293 24.707a1 1 0 0 1 0-1.414L21.586 5H13a1 1 0 1 1 0-2h11a1 1 0 0 1 1 1v11a1 1 0 1 1-2 0V6.414L4.707 24.707a1 1 0 0 1-1.414 0");
}

</style>
