<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="vnr954bes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:envelope-simple-fill" {...props}></Icon>
<style>
:global(.vnr954bes) {
  fill: currentColor;
  d: path("M224 48H32a8 8 0 0 0-8 8v136a16 16 0 0 0 16 16h176a16 16 0 0 0 16-16V56a8 8 0 0 0-8-8m-8 144H40V74.19l82.59 75.71a8 8 0 0 0 10.82 0L216 74.19z");
}

</style>
