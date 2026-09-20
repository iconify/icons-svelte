<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4o0h_nqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:align-center-outline-rounded" {...props}></Icon>
<style>
:global(.l4o0h_nqr) {
  fill: currentColor;
  d: path("M3 13q-.425 0-.712-.288T2 12t.288-.712T3 11h18q.425 0 .713.288T22 12t-.288.713T21 13zm5-3q-.425 0-.712-.288T7 9V8q0-.425.288-.712T8 7h8q.425 0 .713.288T17 8v1q0 .425-.288.713T16 10zm0 7q-.425 0-.712-.288T7 16v-1q0-.425.288-.712T8 14h8q.425 0 .713.288T17 15v1q0 .425-.288.713T16 17z");
}

</style>
