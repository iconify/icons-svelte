<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="apmfevdsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:arrow-drop-down-circle" {...props}></Icon>
<style>
:global(.apmfevdsn) {
  fill: currentColor;
  d: path("M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10s10-4.48 10-10S17.52 2 12 2m0 12l-4-4h8z");
}

</style>
