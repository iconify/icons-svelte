<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bf4t9pbre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:mail-sharp" {...props}></Icon>
<style>
:global(.bf4t9pbre) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm10-7l8-5V6l-8 5l-8-5v2z");
}

</style>
