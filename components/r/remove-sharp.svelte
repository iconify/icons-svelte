<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vgaa_3bxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:remove-sharp" {...props}></Icon>
<style>
:global(.vgaa_3bxl) {
  fill: currentColor;
  d: path("M6 12.5v-1h12v1z");
}

</style>
