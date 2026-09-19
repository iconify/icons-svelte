<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i0vwi3mgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:kreate" {...props}></Icon>
<style>
:global(.i0vwi3mgu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.415 41.276c0 1.624-1.207 2.162-2.414 1.074L16.889 25.129c-.626-.565-.626-1.693 0-2.258L36 5.65c1.207-1.088 2.414-.55 2.414 1.074zM9.585 4.5v39");
}

</style>
