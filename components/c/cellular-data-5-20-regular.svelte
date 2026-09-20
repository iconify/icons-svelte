<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="utlu2lbkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:cellular-data-5-20-regular" {...props}></Icon>
<style>
:global(.utlu2lbkm) {
  fill: currentColor;
  d: path("M4.5 12a.5.5 0 0 1 .492.41L5 12.5v3a.5.5 0 0 1-.992.09L4 15.5v-3a.5.5 0 0 1 .5-.5");
}

</style>
