<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r6zpstb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:crop-5-4-sharp" {...props}></Icon>
<style>
:global(.r6zpstb_t) {
  fill: currentColor;
  d: path("M3 20V4h18v16z");
}

</style>
