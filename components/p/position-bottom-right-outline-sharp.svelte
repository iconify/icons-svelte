<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vezow1_wt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:position-bottom-right-outline-sharp" {...props}></Icon>
<style>
:global(.vezow1_wt) {
  fill: currentColor;
  d: path("M9.385 16.808h8v-2h-8zM4 20V4h16v16zm1-1h14V5H5zM5 5v14z");
}

</style>
