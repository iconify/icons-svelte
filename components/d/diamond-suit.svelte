<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="euu415bms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:diamond-suit" {...props}></Icon>
<style>
:global(.euu415bms) {
  fill: currentColor;
  d: path("M62 32L32 62L2.001 32l30-30z");
}

</style>
