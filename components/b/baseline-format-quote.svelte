<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u82-tjbvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-format-quote" {...props}></Icon>
<style>
:global(.u82-tjbvp) {
  fill: currentColor;
  d: path("M6 17h3l2-4V7H5v6h3zm8 0h3l2-4V7h-6v6h3z");
}

</style>
