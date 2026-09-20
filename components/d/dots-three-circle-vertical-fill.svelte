<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="x_9q9-qet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:dots-three-circle-vertical-fill" {...props}></Icon>
<style>
:global(.x_9q9-qet) {
  fill: currentColor;
  d: path("M232 128a104 104 0 1 0-104 104a104.13 104.13 0 0 0 104-104M116 84a12 12 0 1 1 12 12a12 12 0 0 1-12-12m0 44a12 12 0 1 1 12 12a12 12 0 0 1-12-12m0 44a12 12 0 1 1 12 12a12 12 0 0 1-12-12");
}

</style>
