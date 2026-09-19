<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="duqcu1boc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:henner-plus" {...props}></Icon>
<style>
:global(.duqcu1boc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 27H21v15.5m0-37V21H5.5m37 0H27V5.5m0 37V27h15.5");
}

</style>
