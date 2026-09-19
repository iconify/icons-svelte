<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h6jfcwiyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:easy-fast" {...props}></Icon>
<style>
:global(.h6jfcwiyo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.611 11.668c6.602 9.428 4.608 22.383-4.523 29.389s-22.16 5.58-29.558-3.238C.132 29.003.989 15.923 9.475 8.15C17.96.374 31.065.66 39.203 8.798L12.285 35.715");
}

</style>
