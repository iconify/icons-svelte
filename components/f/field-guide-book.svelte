<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qxzakcchr"/><path class="ajegm28um"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:field-guide-book" {...props}></Icon>
<style>
:global(.ajegm28um) {
  d: path("M14.75 15.5c0-4 1.5-6 3.25-6.5c.25 3.5-.75 6.25-3.25 6.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qxzakcchr) {
  d: path("M12 6C9.5 4.5 6 4.25 3 5v14c3-.75 6.5-.5 9 1c2.5-1.5 6-1.75 9-1V5c-3-.75-6.5-.5-9 1m0 0v14");
}

</style>
