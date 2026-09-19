<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vut_lw_9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:calendar-google-1" {...props}></Icon>
<style>
:global(.vut_lw_9p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.875 20.738l2.25-1.238m0 0v9M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h24l9-9v-24a4 4 0 0 0-4-4m-5 0v37m-19-28v28m28-9h-37m37-19h-28");
}

</style>
