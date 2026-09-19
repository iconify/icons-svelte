<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="o6om72bnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:letter-f" {...props}></Icon>
<style>
:global(.o6om72bnq) {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m10.345 20.61H27.68v6.673h12.854v5.039H27.68v12.166h-6.024V17.512h20.689z");
}

</style>
