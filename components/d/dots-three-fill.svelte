<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="yfgv0hbtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:dots-three-fill" {...props}></Icon>
<style>
:global(.yfgv0hbtu) {
  fill: currentColor;
  d: path("M224 80H32a16 16 0 0 0-16 16v64a16 16 0 0 0 16 16h192a16 16 0 0 0 16-16V96a16 16 0 0 0-16-16M60 140a12 12 0 1 1 12-12a12 12 0 0 1-12 12m68 0a12 12 0 1 1 12-12a12 12 0 0 1-12 12m68 0a12 12 0 1 1 12-12a12 12 0 0 1-12 12");
}

</style>
