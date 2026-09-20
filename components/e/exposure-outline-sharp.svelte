<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vx04fzb3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:exposure-outline-sharp" {...props}></Icon>
<style>
:global(.vx04fzb3z) {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-2h14V5zm9.5-1v-2h-2v-1.5h2v-2H16v2h2V16h-2v2zM6 8.5h5V7H6z");
}

</style>
