<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="fv1z_2_5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:exclude-fill" {...props}></Icon>
<style>
:global(.fv1z_2_5p) {
  fill: currentColor;
  d: path("M240 160a80 80 0 0 1-158.64 14.64a80 80 0 0 0 93.28-93.28A80 80 0 0 1 240 160m-80-80a80.3 80.3 0 0 1 14.64 1.36a80 80 0 1 0-93.28 93.28A80 80 0 0 1 160 80");
}

</style>
