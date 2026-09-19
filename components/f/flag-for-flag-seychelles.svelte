<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="k3zhr6bur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:flag-for-flag-seychelles" {...props}></Icon>
<style>
:global(.k3zhr6bur) {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2M17.148 55.72q-.363-.225-.718-.46l42.34-15.053a28 28 0 0 1-6.652 11.238zm39.291-37.362L14.975 54L36.121 4.306c8.734 1.294 16.162 6.636 20.318 14.052");
}

</style>
