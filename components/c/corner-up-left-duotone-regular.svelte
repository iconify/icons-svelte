<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s1ekoxp9h"/><path class="q8tyuag9f"/><path class="pq65d4pux"/><path class="wuavqcbqp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:corner-up-left-duotone-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pq65d4pux) {
  d: path("M20 20V10H4");
}

:global(.q8tyuag9f) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 5 -5 5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s1ekoxp9h) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 20V10H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wuavqcbqp) {
  d: path("m9 5 -5 5 5 5");
}

</style>
