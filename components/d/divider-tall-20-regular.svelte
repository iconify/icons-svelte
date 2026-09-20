<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yzli95b7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:divider-tall-20-regular" {...props}></Icon>
<style>
:global(.yzli95b7g) {
  fill: currentColor;
  d: path("M9.5 1a.5.5 0 0 1 .5.5v17a.5.5 0 0 1-1 0v-17a.5.5 0 0 1 .5-.5");
}

</style>
