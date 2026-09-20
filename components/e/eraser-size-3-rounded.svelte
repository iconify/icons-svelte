<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6lgqu75d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:eraser-size-3-rounded" {...props}></Icon>
<style>
:global(.h6lgqu75d) {
  fill: currentColor;
  d: path("M8.5 19q-1.45 0-2.475-1.025T5 15.5q0-.675.263-1.325t.762-1.15l7-7q.5-.5 1.15-.763T15.5 5q1.45 0 2.475 1.025T19 8.5q0 .675-.262 1.325t-.763 1.15l-7 7q-.5.5-1.15.763T8.5 19");
}

</style>
