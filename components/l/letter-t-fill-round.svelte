<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mwifcgbsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-t-fill-round" {...props}></Icon>
<style>
:global(.mwifcgbsb) {
  fill: currentColor;
  d: path("M12 3h6a1 1 0 0 1 0 2h-5v15a1 1 0 0 1-2 0V5H6a1 1 0 0 1 0-2Z");
}

</style>
