<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhu9qj-gj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:candlestick-chart-sharp" {...props}></Icon>
<style>
:global(.hhu9qj-gj) {
  fill: currentColor;
  d: path("M7 20v-2H5V6h2V4h2v2h2v12H9v2zm8 0v-5h-2V8h2V4h2v4h2v7h-2v5z");
}

</style>
