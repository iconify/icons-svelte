<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wr7d3fbqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:re-order-vertical-16-regular" {...props}></Icon>
<style>
:global(.wr7d3fbqr) {
  fill: currentColor;
  d: path("M9 13.5v-11a.5.5 0 0 1 .992-.09L10 2.5v11a.5.5 0 0 1-.992.09zm-3 0v-11a.5.5 0 0 1 .992-.09L7 2.5v11a.5.5 0 0 1-.992.09z");
}

</style>
