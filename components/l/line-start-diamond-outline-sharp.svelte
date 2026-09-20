<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vins6khmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:line-start-diamond-outline-sharp" {...props}></Icon>
<style>
:global(.vins6khmq) {
  fill: currentColor;
  d: path("M9 15.348L12.348 12L9 8.652L5.652 12zm0 1.421L4.23 12L9 7.23l4.27 4.27h7.653v1h-7.654zM9 12");
}

</style>
