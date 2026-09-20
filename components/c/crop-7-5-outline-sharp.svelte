<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxhlm2y6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:crop-7-5-outline-sharp" {...props}></Icon>
<style>
:global(.gxhlm2y6d) {
  fill: currentColor;
  d: path("M3 19V5h18v14zm2-2h14V7H5zm0 0V7z");
}

</style>
