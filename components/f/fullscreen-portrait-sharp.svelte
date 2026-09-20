<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y353gab5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:fullscreen-portrait-sharp" {...props}></Icon>
<style>
:global(.y353gab5e) {
  fill: currentColor;
  d: path("M8 18h8V6H8zm12 4H4V2h16z");
}

</style>
