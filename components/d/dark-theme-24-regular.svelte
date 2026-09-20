<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nocfaehej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:dark-theme-24-regular" {...props}></Icon>
<style>
:global(.nocfaehej) {
  fill: currentColor;
  d: path("M12 22c5.523 0 10-4.477 10-10S17.523 2 12 2S2 6.477 2 12s4.477 10 10 10m0-1.5v-17a8.5 8.5 0 0 1 0 17");
}

</style>
