<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qvolz4b2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:auxio" {...props}></Icon>
<style>
:global(.qvolz4b2k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.839 13.745L26.545 3.5v33.352L18.831 44.5l-7.67-7.648l7.67-7.707");
}

</style>
