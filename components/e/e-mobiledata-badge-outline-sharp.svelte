<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thfj-xbcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:e-mobiledata-badge-outline-sharp" {...props}></Icon>
<style>
:global(.thfj-xbcm) {
  fill: currentColor;
  d: path("M8 17h8v-2h-6v-2h5v-2h-5V9h6V7H8zm-5 4V3h18v18zm2-2h14V5H5zM5 5v14z");
}

</style>
