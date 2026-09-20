<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fw9ty_b8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:checkmark-24-filled" {...props}></Icon>
<style>
:global(.fw9ty_b8z) {
  fill: currentColor;
  d: path("m8.5 16.586l-3.793-3.793a1 1 0 0 0-1.414 1.414l4.5 4.5a1 1 0 0 0 1.414 0l11-11a1 1 0 0 0-1.414-1.414z");
}

</style>
