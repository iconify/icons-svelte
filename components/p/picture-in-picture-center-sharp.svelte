<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwu4u_bcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:picture-in-picture-center-sharp" {...props}></Icon>
<style>
:global(.qwu4u_bcv) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm6-5h8V9H8z");
}

</style>
