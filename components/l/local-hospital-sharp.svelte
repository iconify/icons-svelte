<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0exxcbao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:local-hospital-sharp" {...props}></Icon>
<style>
:global(.t0exxcbao) {
  fill: currentColor;
  d: path("M10.5 17h3v-3.5H17v-3h-3.5V7h-3v3.5H7v3h3.5zM3 21V3h18v18z");
}

</style>
