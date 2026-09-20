<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zruhqpb6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:horizontal-align-left" {...props}></Icon>
<style>
:global(.zruhqpb6m) {
  fill: currentColor;
  d: path("M3 20V4h2v16zm9-3l-5-5l5-5l1.4 1.4l-2.6 2.6H21v2H10.8l2.6 2.6z");
}

</style>
