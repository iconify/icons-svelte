<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cn5q2db1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:penup" {...props}></Icon>
<style>
:global(.cn5q2db1h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.036 35.23h14.103L25.386 6.3a1.602 1.602 0 0 0-2.772 0L5.86 35.23h11.06l7.27 7.27V24.34m-4.155-13.474h7.93");
}

</style>
