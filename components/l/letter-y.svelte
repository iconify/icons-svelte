<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="c_ul3gbro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:letter-y" {...props}></Icon>
<style>
:global(.c_ul3gbro) {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m3.198 33.627v10.881h-6.063V35.627L19.096 17.492h7.146l6.023 12.637l5.769-12.637h6.87z");
}

</style>
