<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ue8xzq-ct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-u-turn-down-right-bulk" {...props}></Icon>
<style>
:global(.ue8xzq-ct) {
  fill: currentColor;
  d: path("m21.707 15.707l-4 4a.999.999 0 1 1-1.414-1.414L18.586 16H5a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h8a1 1 0 0 1 0 2H5a.997.997 0 0 0-1 1v6a.997.997 0 0 0 1 1h13.586l-2.293-2.293a.999.999 0 1 1 1.414-1.414l4 4a1 1 0 0 1 0 1.414");
}

</style>
