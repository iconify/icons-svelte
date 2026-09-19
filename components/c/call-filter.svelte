<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="javt86i9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:call-filter" {...props}></Icon>
<style>
:global(.javt86i9c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4m7.993 19.54l4.403 7.917l8.611-17.914");
}

</style>
