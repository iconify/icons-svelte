<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tc_s9209a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:position-bottom-left-outline-sharp" {...props}></Icon>
<style>
:global(.tc_s9209a) {
  fill: currentColor;
  d: path("M6 17h9v-3H6zm-3 4V3h18v18zm2-2h14V5H5zM5 5v14z");
}

</style>
