<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgtd_x-eb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:markunread" {...props}></Icon>
<style>
:global(.fgtd_x-eb) {
  fill: currentColor;
  d: path("M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2m0 4l-8 5l-8-5V6l8 5l8-5z");
}

</style>
