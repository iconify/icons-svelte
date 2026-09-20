<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbh2bdp2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:horizontal-rule-rounded" {...props}></Icon>
<style>
:global(.fbh2bdp2z) {
  fill: currentColor;
  d: path("M5.5 12.5q-.213 0-.356-.144T5 11.999t.144-.356t.356-.143h13q.213 0 .356.144t.144.357t-.144.356t-.356.143z");
}

</style>
