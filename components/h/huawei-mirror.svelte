<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="niddxibvm"/><path class="fsd0axbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:huawei-mirror" {...props}></Icon>
<style>
:global(.fsd0axbji) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.15 24.053a9.563 9.563 0 0 1 4.218-12.356m4.53 24.678V43.4m-8.788.1h17.374");
}

:global(.niddxibvm) {
  cx: 24px;
  cy: 20.438px;
  r: 15.938px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
