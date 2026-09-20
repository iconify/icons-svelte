<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r56g5dama"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:chevron-line-up-outline-sharp" {...props}></Icon>
<style>
:global(.r56g5dama) {
  fill: currentColor;
  d: path("M6 8V6h12v2zm1.4 10.4L6 17l6-6l6 6l-1.4 1.4l-4.6-4.6z");
}

</style>
