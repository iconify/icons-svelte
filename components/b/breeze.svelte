<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kme_1ab3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:breeze" {...props}></Icon>
<style>
:global(.kme_1ab3v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.5 5.5C29.851 5.5 35 10.649 35 17s-5.149 11.5-11.5 11.5H13a7 7 0 1 0 0 14h17.5C36.851 42.5 42 37.351 42 31s-5.149-11.5-11.5-11.5H13a7 7 0 1 1 0-14z");
}

</style>
