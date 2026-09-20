<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nwurvfbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:keyboard-capslock-badge-outline-sharp" {...props}></Icon>
<style>
:global(.nwurvfbog) {
  fill: currentColor;
  d: path("M7.712 16h8.577v-1H7.711zm.688-3.02L12 9.4l3.6 3.58l.689-.688L12 7.985l-4.288 4.307zM4 20V4h16v16zm1-1h14V5H5zM5 5v14z");
}

</style>
