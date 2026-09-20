<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t6klew5pq"/><path class="rtzcjpz7f"/><path class="pq65d4pux"/><path class="wuavqcbqp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:corner-up-left-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pq65d4pux) {
  d: path("M20 20V10H4");
}

:global(.rtzcjpz7f) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 5 -5 5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t6klew5pq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 20V10H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wuavqcbqp) {
  d: path("m9 5 -5 5 5 5");
}

</style>
