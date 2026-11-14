<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ts2u-lvjt"/><path class="j-bp5ef8a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:letter-tiles" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j-bp5ef8a) {
  d: path("m4.5 14l2-4.5l2 4.5m-3.25-1.5h2.5m9.75-3V14");
}

:global(.ts2u-lvjt) {
  d: path("M5.125 7h2.75A2.625 2.625 0 0 1 10.5 9.625v4.75A2.625 2.625 0 0 1 7.875 17h-2.75A2.625 2.625 0 0 1 2.5 14.375v-4.75A2.625 2.625 0 0 1 5.125 7m11 0h2.75A2.625 2.625 0 0 1 21.5 9.625v4.75A2.625 2.625 0 0 1 18.875 17h-2.75a2.625 2.625 0 0 1-2.625-2.625v-4.75A2.625 2.625 0 0 1 16.125 7");
}

</style>
