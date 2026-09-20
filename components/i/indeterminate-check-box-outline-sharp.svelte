<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdmhjibzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:indeterminate-check-box-outline-sharp" {...props}></Icon>
<style>
:global(.bdmhjibzm) {
  fill: currentColor;
  d: path("M7 13h10v-2H7zm-4 8V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
