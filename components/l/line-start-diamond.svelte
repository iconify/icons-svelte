<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hp9dc8bhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:line-start-diamond" {...props}></Icon>
<style>
:global(.hp9dc8bhs) {
  fill: currentColor;
  d: path("M9 16.77L4.23 12L9 7.23l4.27 4.27h7.653v1h-7.654z");
}

</style>
