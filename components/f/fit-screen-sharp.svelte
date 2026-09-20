<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="leqzc6bmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:fit-screen-sharp" {...props}></Icon>
<style>
:global(.leqzc6bmm) {
  fill: currentColor;
  d: path("M20 9V6h-3V4h5v5zM2 9V4h5v2H4v3zm15 11v-2h3v-3h2v5zM2 20v-5h2v3h3v2zm4-4V8h12v8z");
}

</style>
