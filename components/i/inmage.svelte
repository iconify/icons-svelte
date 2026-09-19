<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p13c5lb7i"/><path class="pr421bbws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:inmage" {...props}></Icon>
<style>
:global(.p13c5lb7i) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M24 2.5A21.5 21.5 0 1 1 2.5 24A21.503 21.503 0 0 1 24 2.5Z");
}

:global(.pr421bbws) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M16.517 15.499h14.966a1.02 1.02 0 0 1 1.018 1.018v14.966a1.02 1.02 0 0 1-1.018 1.018H16.517a1.02 1.02 0 0 1-1.018-1.018V16.517a1.02 1.02 0 0 1 1.018-1.018Z");
}

</style>
