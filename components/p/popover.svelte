<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="hmlplkaik"/><path class="bq-ll3dzm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:popover" {...props}></Icon>
<style>
:global(.bq-ll3dzm) {
  d: path("M5.25 10.75h.9l1.6-2.05a.95.95 0 0 1 1.5 0l1.6 2.05h7.9a2.5 2.5 0 0 1 2.5 2.5v5a2.5 2.5 0 0 1-2.5 2.5H5.25a2.5 2.5 0 0 1-2.5-2.5v-5a2.5 2.5 0 0 1 2.5-2.5m1.25 3.5h11m-11 3.25h7");
}

:global(.hmlplkaik) {
  width: 7px;
  height: 3.25px;
  x: 5px;
  y: 2.75px;
  rx: 1.625px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
