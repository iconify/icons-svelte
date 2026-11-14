<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ro61rqmnd"/><path class="sago6lk6a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:api-check" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ro61rqmnd) {
  d: path("M11.95 17.895L10 19l-7.5-4.25v-8.5L10 2l7.5 4.25v8.5l-1.374.779");
}

:global(.sago6lk6a) {
  d: path("M2.5 6.25L10 10.5l7.5-4.25M10 10.5V19m4.75-1l2 2L21 15.75");
}

</style>
