<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjif96bjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:page-footer-outline-sharp" {...props}></Icon>
<style>
:global(.gjif96bjc) {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm0-4V3h18v14zm2-2h14V5H5zm0 0V5z");
}

</style>
