<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rec5gmbbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:post" {...props}></Icon>
<style>
:global(.rec5gmbbj) {
  fill: currentColor;
  d: path("M3 21V3h18v18zm3-7h12v-2H6zm0 3h12v-1.5H6z");
}

</style>
