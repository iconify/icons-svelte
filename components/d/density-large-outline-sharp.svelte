<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqu2z7j_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:density-large-outline-sharp" {...props}></Icon>
<style>
:global(.oqu2z7j_m) {
  fill: currentColor;
  d: path("M3 21v-2h18v2zM3 5V3h18v2z");
}

</style>
