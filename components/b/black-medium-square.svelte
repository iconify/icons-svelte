<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="rf31_lbll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:black-medium-square" {...props}></Icon>
<style>
:global(.rf31_lbll) {
  fill: currentColor;
  d: path("M7 8h48v48H7z");
}

</style>
