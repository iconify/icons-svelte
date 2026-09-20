<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzbsbp-2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:1k-outline-sharp" {...props}></Icon>
<style>
:global(.zzbsbp-2b) {
  fill: currentColor;
  d: path("M12 15h1.5v-2.25L15.25 15h1.825l-2.325-3l2.325-3H15.25l-1.75 2.25V9H12zm-3.5 0H10V9H7v1.5h1.5zM3 21V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
