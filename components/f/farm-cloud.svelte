<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zxks6m76t"/><path class="bguqhzh_p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:farm-cloud" {...props}></Icon>
<style>
:global(.bguqhzh_p) {
  d: path("M12 15c0-1.3-1-2.1-2.5-2c-.1 1.3.9 2.1 2.5 2m0-.75c0-1.55 1-2.75 2.5-2.75c.1 1.6-.9 2.8-2.5 2.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zxks6m76t) {
  d: path("M7 18.5a4 4 0 0 1 0-8a5.5 5.5 0 0 1 11 1a3.5 3.5 0 0 1-1 7Zm5-1.5v-2.75");
}

</style>
