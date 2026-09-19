<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y6kv86zuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:gearbest" {...props}></Icon>
<style>
:global(.y6kv86zuf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 14.972C7.573 26.442 15.141 33.028 24 33.028s16.425-6.58 19.5-18.056H33.094");
}

</style>
