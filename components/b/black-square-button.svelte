<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="poyjmcwjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:black-square-button" {...props}></Icon>
<style>
:global(.poyjmcwjh) {
  fill: currentColor;
  d: path("M2 2v60h60V2zm52 52H10V10h44z");
}

</style>
