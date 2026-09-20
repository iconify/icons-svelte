<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="fcxh8q8kp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:cell-signal-none-light" {...props}></Icon>
<style>
:global(.fcxh8q8kp) {
  fill: currentColor;
  d: path("M46 192v8a6 6 0 0 1-12 0v-8a6 6 0 0 1 12 0");
}

</style>
