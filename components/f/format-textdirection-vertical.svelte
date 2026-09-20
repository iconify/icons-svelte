<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jktoxjyhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:format-textdirection-vertical" {...props}></Icon>
<style>
:global(.jktoxjyhp) {
  fill: currentColor;
  d: path("M6 18v-5q-1.65 0-2.825-1.175T2 9t1.175-2.825T6 5h8v2h-2v11h-2V7H8v11zm12 2l-4-4l1.4-1.4l1.6 1.575V5h2v11.175l1.6-1.6L22 16z");
}

</style>
