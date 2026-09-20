<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="km1x2gb7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-export-up-20-regular" {...props}></Icon>
<style>
:global(.km1x2gb7f) {
  fill: currentColor;
  d: path("M9.646 2.146a.5.5 0 0 1 .708 0l4 4a.5.5 0 0 1-.708.708L10.5 3.707V14.5a.5.5 0 0 1-1 0V3.707L6.354 6.854a.5.5 0 1 1-.708-.708zM4 17.5a.5.5 0 0 1 .5-.5h11a.5.5 0 0 1 0 1h-11a.5.5 0 0 1-.5-.5");
}

</style>
