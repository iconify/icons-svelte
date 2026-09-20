<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mb9a9mb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:jottacloud" {...props}></Icon>
<style>
:global(.mb9a9mb2v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.056 5.5H42.5v24a13 13 0 0 1-13 13h-3.444v-24a13 13 0 0 1 13-13M5.5 26.056h3.444a13 13 0 0 1 13 13V42.5H18.5a13 13 0 0 1-13-13z");
}

</style>
