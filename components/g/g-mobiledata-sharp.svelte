<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gu_wdxieb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:g-mobiledata-sharp" {...props}></Icon>
<style>
:global(.gu_wdxieb) {
  fill: currentColor;
  d: path("M7 17V7h9v2H9v6h5v-2h-2v-2h4v6z");
}

</style>
