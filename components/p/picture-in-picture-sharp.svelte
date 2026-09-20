<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="miv0rd35g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:picture-in-picture-sharp" {...props}></Icon>
<style>
:global(.miv0rd35g) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm9-7h8V7h-8z");
}

</style>
