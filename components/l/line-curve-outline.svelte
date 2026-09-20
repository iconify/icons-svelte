<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kodf7cbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:line-curve-outline" {...props}></Icon>
<style>
:global(.kodf7cbhp) {
  fill: currentColor;
  d: path("M18 20q0-2.9-1.1-5.45t-3-4.45t-4.45-3T4 6V4q3.3 0 6.213 1.263T15.3 8.7t3.438 5.088T20 20z");
}

</style>
