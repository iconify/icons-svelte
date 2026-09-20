<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xl1-ijbaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:calendar-view-day-sharp" {...props}></Icon>
<style>
:global(.xl1-ijbaw) {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm0-4V7h18v10zM3 5V3h18v2z");
}

</style>
