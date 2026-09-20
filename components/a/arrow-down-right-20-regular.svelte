<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gs-hhuboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-down-right-20-regular" {...props}></Icon>
<style>
:global(.gs-hhuboj) {
  fill: currentColor;
  d: path("M8.5 16a.5.5 0 0 0 0 1h8a.5.5 0 0 0 .5-.5v-8a.5.5 0 0 0-1 0v6.793L3.854 3.146a.5.5 0 1 0-.708.708L15.293 16z");
}

</style>
