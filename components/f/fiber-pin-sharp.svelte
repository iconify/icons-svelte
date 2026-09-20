<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_bgycgcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:fiber-pin-sharp" {...props}></Icon>
<style>
:global(.p_bgycgcd) {
  fill: currentColor;
  d: path("M5 15h1.5v-2H10V9H5zm6.25 0h1.5V9h-1.5zM14 15h1.25v-3.5L17.8 15H19V9h-1.25v3.5L15.25 9H14zm-7.5-3.5v-1h2v1zM2 20V4h20v16z");
}

</style>
