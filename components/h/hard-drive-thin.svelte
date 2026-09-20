<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="v62wy1but"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:hard-drive-thin" {...props}></Icon>
<style>
:global(.v62wy1but) {
  fill: currentColor;
  d: path("M224 68H32a12 12 0 0 0-12 12v96a12 12 0 0 0 12 12h192a12 12 0 0 0 12-12V80a12 12 0 0 0-12-12m4 108a4 4 0 0 1-4 4H32a4 4 0 0 1-4-4V80a4 4 0 0 1 4-4h192a4 4 0 0 1 4 4Zm-32-48a8 8 0 1 1-8-8a8 8 0 0 1 8 8");
}

</style>
