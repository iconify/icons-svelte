<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g1iijbccu"/><path class="hm5i0fbmn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:barn-venue" {...props}></Icon>
<style>
:global(.g1iijbccu) {
  d: path("M3 21.5V11l2.5-5L12 2.5L18.5 6l2.5 5v10.5Z");
}

:global(.hm5i0fbmn) {
  d: path("M7.5 21.5v-9h9v9m-9-9l9 9m0-9l-9 9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
