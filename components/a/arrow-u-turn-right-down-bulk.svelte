<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vr_77c_ku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-u-turn-right-down-bulk" {...props}></Icon>
<style>
:global(.vr_77c_ku) {
  fill: currentColor;
  d: path("m14.293 21.707l-4-4a.999.999 0 1 1 1.414-1.414L14 18.586V5a.997.997 0 0 0-1-1H7a.997.997 0 0 0-1 1v8a1 1 0 0 1-2 0V5a3 3 0 0 1 3-3h6a3 3 0 0 1 3 3v13.586l2.293-2.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0");
}

</style>
