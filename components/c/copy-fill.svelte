<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="lrrklnbav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:copy-fill" {...props}></Icon>
<style>
:global(.lrrklnbav) {
  fill: currentColor;
  d: path("M216 32H88a8 8 0 0 0-8 8v40H40a8 8 0 0 0-8 8v128a8 8 0 0 0 8 8h128a8 8 0 0 0 8-8v-40h40a8 8 0 0 0 8-8V40a8 8 0 0 0-8-8m-8 128h-32V88a8 8 0 0 0-8-8H96V48h112Z");
}

</style>
