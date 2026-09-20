<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irxjehbbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:remove-outline-rounded" {...props}></Icon>
<style>
:global(.irxjehbbg) {
  fill: currentColor;
  d: path("M6.5 12.5q-.213 0-.356-.144T6 11.999t.144-.356t.356-.143h11q.213 0 .356.144t.144.357t-.144.356t-.356.143z");
}

</style>
