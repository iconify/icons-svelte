<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l1qeu0fpc"/><path class="gnv-gn0oh"/><path class="d20u3lqwj"/><path class="kt7x9fb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:private-screenshots" {...props}></Icon>
<style>
:global(.d20u3lqwj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.741 22.552h8.517c.323 0 .585.261.585.584v6.295a.585.585 0 0 1-.585.585h-8.517a.585.585 0 0 1-.585-.585v-6.295c0-.323.262-.584.585-.584");
}

:global(.gnv-gn0oh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.26 11.57h13.48c1.295 0 2.345 1.141 2.345 2.55v19.762c0 1.408-1.05 2.55-2.345 2.55H17.26c-1.294 0-2.344-1.142-2.344-2.55V14.12c0-1.409 1.05-2.55 2.345-2.55");
}

:global(.kt7x9fb4l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.794 22.552v-1.343a3.203 3.203 0 0 1 6.406 0v1.343");
}

:global(.l1qeu0fpc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.604 4.5h18.792c1.805 0 3.269 1.79 3.269 4v31c0 2.21-1.464 4-3.269 4H14.604c-1.805 0-3.269-1.79-3.269-4v-31c0-2.21 1.464-4 3.269-4");
}

</style>
