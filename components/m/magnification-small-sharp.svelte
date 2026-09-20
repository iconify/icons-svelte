<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ehkk5bc9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:magnification-small-sharp" {...props}></Icon>
<style>
:global(.ehkk5bc9y) {
  fill: currentColor;
  d: path("M5 11h4V7H5zm-3 9V4h20v16z");
}

</style>
