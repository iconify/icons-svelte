<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="momavlbkj"/><path class="f9ju_qbub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:kakao-bank" {...props}></Icon>
<style>
:global(.f9ju_qbub) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21 14.75h4v18.5h-4z");
}

:global(.momavlbkj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29 4.5H8.5v39H29c5.799 0 10.5-4.701 10.5-10.5a10.5 10.5 0 0 0-5.103-9.004A10.5 10.5 0 0 0 39.5 15c0-5.799-4.701-10.5-10.5-10.5");
}

</style>
