<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="gw8vy3bik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:hard-drive-fill" {...props}></Icon>
<style>
:global(.gw8vy3bik) {
  fill: currentColor;
  d: path("M224 64H32a16 16 0 0 0-16 16v96a16 16 0 0 0 16 16h192a16 16 0 0 0 16-16V80a16 16 0 0 0-16-16m-36 76a12 12 0 1 1 12-12a12 12 0 0 1-12 12");
}

</style>
