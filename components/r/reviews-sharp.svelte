<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilawgs16q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:reviews-sharp" {...props}></Icon>
<style>
:global(.ilawgs16q) {
  fill: currentColor;
  d: path("M2 22V2h20v16H6zm7.075-7.75L12 12.475l2.925 1.775l-.775-3.325l2.6-2.25l-3.425-.275L12 5.25L10.675 8.4l-3.425.275l2.6 2.25z");
}

</style>
