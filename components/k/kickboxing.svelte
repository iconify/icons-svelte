<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g8a_216kn"/><path class="areq-7y_z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:kickboxing" {...props}></Icon>
<style>
:global(.areq-7y_z) {
  d: path("m4.5 7.5l1 3l3.25-1");
}

:global(.g8a_216kn) {
  d: path("M5.5 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m3 3.5l1 5.5L8 21m1.5-7.5l11-4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
