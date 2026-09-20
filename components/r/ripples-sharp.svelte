<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rrjumob-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:ripples-sharp" {...props}></Icon>
<style>
:global(.rrjumob-o) {
  fill: currentColor;
  d: path("M13.55 5q-.275.45-.413.963T13 7q0 1.65 1.175 2.825T17 11q.525 0 1.038-.137T19 10.45V5zM3 21V3h18v18z");
}

</style>
