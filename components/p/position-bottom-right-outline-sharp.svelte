<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwkv2bcmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:position-bottom-right-outline-sharp" {...props}></Icon>
<style>
:global(.dwkv2bcmj) {
  fill: currentColor;
  d: path("M9 17h9v-3H9zm-6 4V3h18v18zm2-2h14V5H5zM5 5v14z");
}

</style>
