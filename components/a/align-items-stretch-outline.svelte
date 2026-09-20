<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-nr8zbtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:align-items-stretch-outline" {...props}></Icon>
<style>
:global(.h-nr8zbtq) {
  fill: currentColor;
  d: path("M7 18V6h3v12zm7 0V6h3v12zM2 4V2h20v2zm0 18v-2h20v2z");
}

</style>
