<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kiwuyvb3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:oil-barrel-sharp" {...props}></Icon>
<style>
:global(.kiwuyvb3p) {
  fill: currentColor;
  d: path("M3 21v-2h2v-6H3v-2h2V5H3V3h18v2h-2v6h2v2h-2v6h2v2zm11.125-5.863Q15 14.276 15 13.05q0-.975-.562-1.675T12 8.5q-1.875 2.15-2.437 2.863T9 13.05q0 1.225.875 2.088T12 16t2.125-.862");
}

</style>
