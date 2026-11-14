<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j8bxj4b5o"/><path class="gtdkf60xt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:arrow-split" {...props}></Icon>
<style>
:global(.gtdkf60xt) {
  d: path("M4.75 10.5V5.75H9.5m5 0h4.75v4.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j8bxj4b5o) {
  d: path("M12 21v-8L5 6m7 7l7-7");
}

</style>
