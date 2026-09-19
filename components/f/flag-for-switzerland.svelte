<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="xszgv7twv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:flag-for-switzerland" {...props}></Icon>
<style>
:global(.xszgv7twv) {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m14.75 34.917h-9.833v9.833h-9.834v-9.833H17.25v-9.834h9.833V17.25h9.834v9.833h9.833z");
}

</style>
