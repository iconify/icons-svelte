<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="aifeoxcub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:freezeyou" {...props}></Icon>
<style>
:global(.aifeoxcub) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 38.024c1.033-3.529 3.47-8.057 5.986-8.057c4.772 0 6.409 10.55 13.674 10.55c7.844 0 16.475-15.047 17.34-33.033");
}

</style>
