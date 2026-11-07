<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g3_5jacow"/><path class="qf8vl9i5t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:alarm-off-duocolor-sharp" {...props}></Icon>
<style>
:global(.g3_5jacow) {
  stroke-opacity: 0.4;
  d: path("m3 6l2-2m13-1l3 3M3 2l19 19");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qf8vl9i5t) {
  d: path("M7.432 6.432a8 8 0 1 0 11.137 11.137M20 13a8 8 0 0 0-8-8");
}

</style>
