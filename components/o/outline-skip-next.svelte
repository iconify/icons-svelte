<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c1x6nphmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-skip-next" {...props}></Icon>
<style>
:global(.c1x6nphmt) {
  fill: currentColor;
  d: path("m6 18l8.5-6L6 6zm2-8.14L11.03 12L8 14.14zM16 6h2v12h-2z");
}

</style>
