<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n889bjj8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:bookmark-sharp" {...props}></Icon>
<style>
:global(.n889bjj8d) {
  fill: currentColor;
  d: path("M6 19.5V4h12v15.5l-6-2.583z");
}

</style>
