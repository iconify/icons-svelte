<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3easlsll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:auto-awesome-motion-sharp" {...props}></Icon>
<style>
:global(.o3easlsll) {
  fill: currentColor;
  d: path("M10 22V10h12v12zm-4-4V6h12v2H8v10zm-4-4V2h12v2H4v10z");
}

</style>
