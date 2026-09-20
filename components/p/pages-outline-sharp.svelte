<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k88m_ab5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:pages-outline-sharp" {...props}></Icon>
<style>
:global(.k88m_ab5c) {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-2h14V5H5zM5 5v14zm4.075 11.25L12 14.475l2.925 1.775l-.775-3.325l2.6-2.25l-3.425-.275L12 7.25l-1.325 3.15l-3.425.275l2.6 2.25z");
}

</style>
