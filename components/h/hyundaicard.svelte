<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vl39y_2wf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:hyundaicard" {...props}></Icon>
<style>
:global(.vl39y_2wf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 28.216v-4.432a4 4 0 0 1 4-4h31a4 4 0 0 1 4 4v4.432");
}

</style>
