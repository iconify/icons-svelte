<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vepl3kbui"/><circle class="ivoeacboo"/><circle class="wkxw5hbfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:laresmart" {...props}></Icon>
<style>
:global(.ivoeacboo) {
  cx: 24px;
  cy: 24px;
  r: 12.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.vepl3kbui) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5s1.361 6 4.861 6l.076-.033A18.5 18.5 0 0 0 5.5 24c0 10.217 8.283 18.5 18.5 18.5h18.5s-1.361-6-4.861-6l-.077.033A18.5 18.5 0 0 0 42.5 24c0-10.217-8.283-18.5-18.5-18.5z");
}

:global(.wkxw5hbfm) {
  cx: 24px;
  cy: 24px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
