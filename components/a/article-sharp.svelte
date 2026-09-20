<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rkbpaqb2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:article-sharp" {...props}></Icon>
<style>
:global(.rkbpaqb2o) {
  fill: currentColor;
  d: path("M7 17h7v-2H7zm0-4h10v-2H7zm0-4h10V7H7zM3 21V3h18v18z");
}

</style>
