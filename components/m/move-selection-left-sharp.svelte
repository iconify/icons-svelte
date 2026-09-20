<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="efoex2ifw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:move-selection-left-sharp" {...props}></Icon>
<style>
:global(.efoex2ifw) {
  fill: currentColor;
  d: path("M2 18V6h12v12zM16 8V6h2v2zm0 10v-2h2v2zm4-10V6h2v2zm0 5v-2h2v2zm0 5v-2h2v2z");
}

</style>
