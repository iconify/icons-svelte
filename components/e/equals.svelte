<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="cic2vmnms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:equals" {...props}></Icon>
<style>
:global(.cic2vmnms) {
  fill: currentColor;
  d: path("M224 160a8 8 0 0 1-8 8H40a8 8 0 0 1 0-16h176a8 8 0 0 1 8 8M40 104h176a8 8 0 0 0 0-16H40a8 8 0 0 0 0 16");
}

</style>
