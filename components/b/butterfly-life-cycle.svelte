<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wupwf76yp"/><path class="ib0-f4xja"/><path class="s63xacceo"/><path class="newugoi0v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:butterfly-life-cycle" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ib0-f4xja) {
  d: path("M16.75 3.773a9.5 9.5 0 0 1 0 16.454");
}

:global(.newugoi0v) {
  d: path("m5.25 3.25l2 .5l-.5 2");
}

:global(.s63xacceo) {
  d: path("m18.75 20.75l-2-.5l.5-2m-10 1.977a9.5 9.5 0 0 1 0-16.454");
}

:global(.wupwf76yp) {
  d: path("M12 12c-1.5-4-5-4-5-1.5c0 2 1.5 3 2.5 3.25C8.75 15.5 10.75 16.5 12 12m0 0c1.5-4 5-4 5-1.5c0 2-1.5 3-2.5 3.25c.75 1.75-1.25 2.75-2.5-1.75");
}

</style>
