<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljumgubvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:1k-plus-outline-sharp" {...props}></Icon>
<style>
:global(.ljumgubvw) {
  fill: currentColor;
  d: path("M16.5 14h1v-1.5H19v-1h-1.5V10h-1v1.5H15v1h1.5zm-6 1H12v-2.25L13.75 15h1.825l-2.325-3l2.325-3H13.75L12 11.25V9h-1.5zm-3 0H9V9H6v1.5h1.5zM3 21V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
