<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="uktz89k5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-v1:large-blue-diamond" {...props}></Icon>
<style>
:global(.uktz89k5k) {
  fill: var(--svg-color--1b75bb, #1b75bb);
  d: path("M63 32L32 62.999L1 32L32 1");
}

</style>
