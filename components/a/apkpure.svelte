<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q0hj_fboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:apkpure" {...props}></Icon>
<style>
:global(.q0hj_fboi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.1 4.5L4.73 33.8l4.76 9.7l19.12-39zm24.17 28.7l-5.05 10.3l-5.05-10.3zM28.61 4.5l9.32 19l-4.76 9.7l-9.31-19zM19.05 24h9.61m-14.12 9.21h18.63");
}

</style>
