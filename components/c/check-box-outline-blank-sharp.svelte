<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6ebjggta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:check-box-outline-blank-sharp" {...props}></Icon>
<style>
:global(.y6ebjggta) {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-2h14V5H5z");
}

</style>
