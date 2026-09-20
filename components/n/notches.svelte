<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="mh6i5obdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:notches" {...props}></Icon>
<style>
:global(.mh6i5obdq) {
  fill: currentColor;
  d: path("m213.66 133.66l-80 80a8 8 0 0 1-11.32-11.32l80-80a8 8 0 0 1 11.32 11.32m-16-99.32a8 8 0 0 0-11.32 0l-152 152a8 8 0 0 0 11.32 11.32l152-152a8 8 0 0 0 0-11.32");
}

</style>
