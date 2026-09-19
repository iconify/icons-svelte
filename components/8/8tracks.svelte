<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="myh69jvxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:8tracks" {...props}></Icon>
<style>
:global(.myh69jvxj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 20.917V14.75A9.25 9.25 0 1 1 33.25 24h-18.5A9.25 9.25 0 1 0 24 33.25v-6.167");
}

</style>
