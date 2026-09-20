<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfo2jdbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:device-band-sharp" {...props}></Icon>
<style>
:global(.tfo2jdbyw) {
  fill: currentColor;
  d: path("M8 22V9H7V6h1V2h8v4h1v3h-1v13z");
}

</style>
