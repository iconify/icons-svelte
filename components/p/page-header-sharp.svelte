<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c6hs-wbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:page-header-sharp" {...props}></Icon>
<style>
:global(.c6hs-wbwx) {
  fill: currentColor;
  d: path("M3 5V3h18v2zm0 16V7h18v14z");
}

</style>
