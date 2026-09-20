<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqy_j3b3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:lte-mobiledata-rounded" {...props}></Icon>
<style>
:global(.aqy_j3b3i) {
  fill: currentColor;
  d: path("M4 15V9q0-.425.288-.712T5 8t.713.288T6 9v5h2q.425 0 .713.288T9 15t-.288.713T8 16H5q-.425 0-.712-.288T4 15m7-5h-1q-.425 0-.712-.288T9 9t.288-.712T10 8h4q.425 0 .713.288T15 9t-.288.713T14 10h-1v5q0 .425-.288.713T12 16t-.712-.288T11 15zm5 5V9q0-.425.288-.712T17 8h3q.425 0 .713.288T21 9t-.288.713T20 10h-2v1h2q.425 0 .713.288T21 12t-.288.713T20 13h-2v1h2q.425 0 .713.288T21 15t-.288.713T20 16h-3q-.425 0-.712-.288T16 15");
}

</style>
