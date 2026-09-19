<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y2sq7mxmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mitsubishi" {...props}></Icon>
<style>
:global(.y2sq7mxmt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 7.044l6.32 10.714L24 28.472l-6.32-10.637zm0 21.43h12.333L42.5 38.956H30.167zm0 0H11.667L5.5 38.956h12.333z");
}

</style>
