<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tr97m0b_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:aspect-ratio-sharp" {...props}></Icon>
<style>
:global(.tr97m0b_u) {
  fill: currentColor;
  d: path("M14 17h5v-5h-2v3h-3zm-9-5h2V9h3V7H5zm-3 8V4h20v16z");
}

</style>
