<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibepfewaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:north-west" {...props}></Icon>
<style>
:global(.ibepfewaa) {
  fill: currentColor;
  d: path("M18.6 20L7 8.4V15H5V5h10v2H8.4L20 18.6z");
}

</style>
