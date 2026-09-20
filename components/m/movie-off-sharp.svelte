<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydgxskbir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:movie-off-sharp" {...props}></Icon>
<style>
:global(.ydgxskbir) {
  fill: currentColor;
  d: path("M2 20V4h2l16 16zm20-.875L6.85 4H8.5l1.675 3.325l.675.675h2.65l-2-4H14l2 4h3l-2-4h5zm-2.225 3.5l-18.4-18.4L2.8 2.8l18.4 18.4z");
}

</style>
