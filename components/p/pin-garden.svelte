<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l7hk0t9tq"/><path class="u96rjlarj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pin-garden" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l7hk0t9tq) {
  d: path("M7.5 3.5L9.75 6L12 3l2.25 3l2.25-2.5v5a4.5 4.5 0 0 1-9 0ZM12 13v8.5m0-2c-3.5 0-6-2.25-6-5.5c3.5 0 6 2.25 6 5.5");
}

:global(.u96rjlarj) {
  d: path("M12 17.5c0-3.25 2.5-5.5 6-5.5c0 3.25-2.5 5.5-6 5.5");
}

</style>
