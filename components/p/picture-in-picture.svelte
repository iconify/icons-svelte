<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="v1k5nbbll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:picture-in-picture" {...props}></Icon>
<style>
:global(.v1k5nbbll) {
  fill: currentColor;
  d: path("M216 48H40a16 16 0 0 0-16 16v128a16 16 0 0 0 16 16h176a16 16 0 0 0 16-16V64a16 16 0 0 0-16-16M40 64h176v56h-80a8 8 0 0 0-8 8v64H40Zm176 128h-72v-56h72z");
}

</style>
