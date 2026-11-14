<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mrsz7c4hi"/><path class="zn8hh5egl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:coveralls" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mrsz7c4hi) {
  d: path("m9.5 3l-4 1l-3 8.5l2.5 1L7 8v13h3.5l1.5-6.5l1.5 6.5H17V8l2 5.5l2.5-1l-3-8.5l-4-1q-2.5 2.5-5 0");
}

:global(.zn8hh5egl) {
  d: path("M9.75 7.5v4h4.5v-4Z");
}

</style>
