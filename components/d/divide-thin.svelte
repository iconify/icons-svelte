<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="w7n88fbbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:divide-thin" {...props}></Icon>
<style>
:global(.w7n88fbbm) {
  fill: currentColor;
  d: path("M220 128a4 4 0 0 1-4 4H40a4 4 0 0 1 0-8h176a4 4 0 0 1 4 4m-92-52a12 12 0 1 0-12-12a12 12 0 0 0 12 12m0 104a12 12 0 1 0 12 12a12 12 0 0 0-12-12");
}

</style>
