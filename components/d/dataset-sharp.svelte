<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzhcejhfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:dataset-sharp" {...props}></Icon>
<style>
:global(.jzhcejhfi) {
  fill: currentColor;
  d: path("M3 21V3h18v18zm4-10h4V7H7zm6 0h4V7h-4zm-6 6h4v-4H7zm6 0h4v-4h-4z");
}

</style>
