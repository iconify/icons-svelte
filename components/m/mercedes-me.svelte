<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="i1pf-qb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mercedes-me" {...props}></Icon>
<style>
:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.i1pf-qb8v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 24V2.5M24 24L5.38 34.75M24 24l18.62 10.75M24 24v3.14M24 24l2.72-1.57M24 24l-2.72-1.57m0 0L24 2.5m2.72 19.93L24 2.5m18.62 32.25l-15.9-12.32M24 27.14l18.62 7.61m-37.24 0L24 27.14m-2.72-4.71L5.38 34.75");
}

</style>
