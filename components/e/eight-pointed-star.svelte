<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="m67nmpbmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:eight-pointed-star" {...props}></Icon>
<style>
:global(.m67nmpbmx) {
  fill: currentColor;
  d: path("M37.834 34.414L62 32l-24.166-2.417l15.38-18.797l-18.798 15.381L32 2l-2.417 24.167l-18.797-15.381l15.38 18.797L2 32l24.166 2.414l-15.38 18.799l18.797-15.379L32 62l2.416-24.166l18.798 15.379z");
}

</style>
