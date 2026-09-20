<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhl1nkbvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:expand-less-sharp" {...props}></Icon>
<style>
:global(.xhl1nkbvf) {
  fill: currentColor;
  d: path("m7.4 15.375l-1.4-1.4l6-6l6 6l-1.4 1.4l-4.6-4.6z");
}

</style>
