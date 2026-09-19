<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hbiniccpo"/><path class="nmhw6dbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-pin-off" {...props}></Icon>
<style>
:global(.hbiniccpo) {
  fill: currentColor;
  d: path("m9 9l7 7h-3v4l-1 3l-1-3v-4H6v-3l3-3zm8-7v2l-2 1v5l3 3v2.461L12.27 9.73L9 6.46V5L7 4V2z");
}

:global(.nmhw6dbmm) {
  fill: currentColor;
  d: path("M2.27 2.27L1 3.54L20.46 23l1.27-1.27L11 11z");
}

</style>
