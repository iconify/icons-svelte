<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wscgdub1g"/><path class="b4w7efbxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:founder-securities" {...props}></Icon>
<style>
:global(.b4w7efbxv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22 5.5L5.5 22v20.5H26L42.5 26V5.5z");
}

:global(.wscgdub1g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.75 13.75h20.5v20.5h-20.5z");
}

</style>
