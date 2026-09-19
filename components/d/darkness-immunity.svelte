<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j1ki6n9lp"/><circle class="unxnw5biy"/><path class="br_27s2jj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:darkness-immunity" {...props}></Icon>
<style>
:global(.br_27s2jj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.632 29.443V18.557h3.606c2.585 0 4.762 2.177 4.762 4.763v1.36c0 2.586-2.177 4.763-4.762 4.763z");
}

:global(.j1ki6n9lp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m45.5 24l-6.289 6.29v8.921H30.29L24 45.5l-6.29-6.289H8.79V30.29L2.5 24l6.29-6.29V8.79h8.92L24 2.5l6.29 6.29h8.921v8.92z");
}

:global(.unxnw5biy) {
  cx: 24px;
  cy: 24px;
  r: 11.516px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
