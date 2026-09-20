<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qgb62ubid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ica" {...props}></Icon>
<style>
:global(.qgb62ubid) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5 14.764v18.472m38 0l-8.944-18.472l-6.425 13.27a9.236 9.236 0 1 1-4.015-12.211m17.486 13.494h-8.52");
}

</style>
