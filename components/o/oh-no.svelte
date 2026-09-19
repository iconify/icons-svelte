<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="byngv_uhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:oh-no" {...props}></Icon>
<style>
:global(.byngv_uhh) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M22.5 14A8.5 8.5 0 1 1 14 5.5a8.5 8.5 0 0 1 8.5 8.5Zm20 0A8.5 8.5 0 1 1 34 5.5a8.5 8.5 0 0 1 8.5 8.5Zm0 20a8.5 8.5 0 1 1-8.5-8.5a8.5 8.5 0 0 1 8.5 8.5Z");
}

</style>
