<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="xwrxm6b6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:avocado-fill" {...props}></Icon>
<style>
:global(.xwrxm6b6v) {
  fill: currentColor;
  d: path("m211 130.66l-29.8-84.19a56 56 0 0 0-106-1.14l-29.51 83.5A88 88 0 1 0 211 130.66M128 200a40 40 0 1 1 40-40a40 40 0 0 1-40 40");
}

</style>
