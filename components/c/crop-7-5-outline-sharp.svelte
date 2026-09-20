<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uw4wfdc_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:crop-7-5-outline-sharp" {...props}></Icon>
<style>
:global(.uw4wfdc_s) {
  fill: currentColor;
  d: path("M4 18V6h16v12zm1-1h14V7H5zm0 0V7z");
}

</style>
