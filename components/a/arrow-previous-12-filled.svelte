<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="dcesrob7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-previous-12-filled" {...props}></Icon>
<style>
:global(.dcesrob7j) {
  fill: currentColor;
  d: path("m6.81 6l2.72-2.72a.75.75 0 0 0-1.06-1.06L5.22 5.47a.75.75 0 0 0 0 1.06l3.25 3.25a.75.75 0 0 0 1.06-1.06zM3 2.75a.75.75 0 0 0-1.5 0v6.5a.75.75 0 0 0 1.5 0z");
}

</style>
