<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwawoi6tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:monitor-weight-outline-sharp" {...props}></Icon>
<style>
:global(.rwawoi6tr) {
  fill: currentColor;
  d: path("M14.125 11.125Q15 10.25 15 9t-.875-2.125T12 6t-2.125.875T9 9t.875 2.125T12 12t2.125-.875M10 9.5v-1h1v1zm1.5 0v-1h1v1zm1.5 0v-1h1v1zM3 21V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
