<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcc63cbuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:auto-read-play-sharp" {...props}></Icon>
<style>
:global(.rcc63cbuv) {
  fill: currentColor;
  d: path("m10 14l6-4l-6-4zm-8 8V2h20v16H6z");
}

</style>
