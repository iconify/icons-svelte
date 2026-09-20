<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aap6mqbnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:calendar-view-day-outline-sharp" {...props}></Icon>
<style>
:global(.aap6mqbnn) {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm0-4V7h18v10zm2-2h14V9H5zM3 5V3h18v2zm2 10V9z");
}

</style>
