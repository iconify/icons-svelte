<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jy5-ernil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:functions" {...props}></Icon>
<style>
:global(.jy5-ernil) {
  fill: currentColor;
  d: path("M6 20v-2l6.5-6L6 6V4h12v3h-7.225l5.375 5l-5.375 5H18v3z");
}

</style>
