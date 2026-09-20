<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gccnyv_vg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:r-mobiledata-outline-sharp" {...props}></Icon>
<style>
:global(.gccnyv_vg) {
  fill: currentColor;
  d: path("M3 10V3h6v4.277H7.723L8.885 10H7.846l-1.15-2.65H4V10zm1-3.65h4V4H4z");
}

</style>
