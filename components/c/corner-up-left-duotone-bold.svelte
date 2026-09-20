<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="s_fg2fb6v"/><path class="mlq5dybnn"/><path class="pq65d4pux"/><path class="wuavqcbqp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:corner-up-left-duotone-bold" {...props}></Icon>
<style>
:global(.mlq5dybnn) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 5 -5 5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pq65d4pux) {
  d: path("M20 20V10H4");
}

:global(.s_fg2fb6v) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 20V10H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wuavqcbqp) {
  d: path("m9 5 -5 5 5 5");
}

</style>
