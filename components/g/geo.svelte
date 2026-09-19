<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wbf7rtnyz"/><path class="kgs5dvbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:geo" {...props}></Icon>
<style>
:global(.kgs5dvbde) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.75 20.25l-.3 2.3l-2.3.3l-.3 2.3l-2.3.3l-.3 2.3");
}

:global(.wbf7rtnyz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.5 24l6.5 6.5l6.5-6.5l-6.5-6.5l-13 13l-6.5-6.5l6.5-6.5m-13 0L4.5 24l6.5 6.5l6.5-6.5l-3.25-3.25l-3.9 3.9");
}

</style>
