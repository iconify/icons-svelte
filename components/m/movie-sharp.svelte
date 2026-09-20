<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wg7k-kxmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:movie-sharp" {...props}></Icon>
<style>
:global(.wg7k-kxmt) {
  fill: currentColor;
  d: path("M2 20V4h2l2 4h3L7 4h2l2 4h3l-2-4h2l2 4h3l-2-4h5v16z");
}

</style>
