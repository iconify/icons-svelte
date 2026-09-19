<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwu8l7bop"/><path class="zysbdqb-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-add-chart" {...props}></Icon>
<style>
:global(.dwu8l7bop) {
  fill: currentColor;
  d: path("M19 19H5V5h9V3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2v-9h-2z");
}

:global(.zysbdqb-t) {
  fill: currentColor;
  d: path("M15 13h2v4h-2zm-8-3h2v7H7zm4-3h2v10h-2zm8-2V3h-2v2h-2v2h2v2h2V7h2V5z");
}

</style>
