<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yr_mosbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:float-landscape-2-sharp" {...props}></Icon>
<style>
:global(.yr_mosbdc) {
  fill: currentColor;
  d: path("M13 14h5V8h-5zM2 20V4h20v16z");
}

</style>
