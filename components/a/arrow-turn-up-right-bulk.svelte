<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jshi5b63l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-turn-up-right-bulk" {...props}></Icon>
<style>
:global(.jshi5b63l) {
  fill: currentColor;
  d: path("M14.586 9H9a.997.997 0 0 0-1 1v11a1 1 0 0 1-2 0V10a3 3 0 0 1 3-3h5.586l-3.293-3.293a.999.999 0 1 1 1.414-1.414l5 5a1 1 0 0 1 0 1.414l-5 5a.999.999 0 1 1-1.414-1.414Z");
}

</style>
