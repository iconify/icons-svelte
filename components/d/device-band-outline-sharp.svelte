<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcl-y3b7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:device-band-outline-sharp" {...props}></Icon>
<style>
:global(.zcl-y3b7h) {
  fill: currentColor;
  d: path("M8 22V9H7V6h1V2h8v4h1v3h-1v13zm2-13.5V20h4V8.5zm0-2h4V4h-4zm0 2h4zm0-2h4z");
}

</style>
