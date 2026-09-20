<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gcqi3_ujf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-circle-up-right-24-filled" {...props}></Icon>
<style>
:global(.gcqi3_ujf) {
  fill: currentColor;
  d: path("M12 22C6.477 22 2 17.523 2 12S6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10M8.75 9.5h4.74l-5.268 5.217a.75.75 0 1 0 1.056 1.066L14.5 10.61v4.639a.75.75 0 0 0 1.5 0v-6.5a.75.75 0 0 0-.75-.75h-6.5a.75.75 0 0 0 0 1.5");
}

</style>
