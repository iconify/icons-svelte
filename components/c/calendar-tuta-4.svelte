<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k6kwpk9-l"/><path class="bag4m3bbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:calendar-tuta-4" {...props}></Icon>
<style>
:global(.bag4m3bbr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 42.27h28.377L42.5 13.893H14.123zm37-28.428H14.123L5.5 5.73h28.377zM5.5 42.27V5.73");
}

:global(.k6kwpk9-l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.773 35.2l4.403-14.4l-10.712 9.72h9.54");
}

</style>
