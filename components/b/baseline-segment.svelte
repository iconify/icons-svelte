<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gngncypfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-segment" {...props}></Icon>
<style>
:global(.gngncypfs) {
  fill: currentColor;
  d: path("M9 18h12v-2H9zM3 6v2h18V6zm6 7h12v-2H9z");
}

</style>
