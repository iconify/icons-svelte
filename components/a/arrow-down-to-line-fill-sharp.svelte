<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5yo4z6ac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-down-to-line-fill-sharp" {...props}></Icon>
<style>
:global(.z5yo4z6ac) {
  fill: currentColor;
  d: path("M7.293 12.707a.999.999 0 1 1 1.414-1.414L11 13.586V4a1 1 0 0 1 2 0v9.586l2.293-2.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0ZM18 19a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Z");
}

</style>
