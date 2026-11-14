<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cwhhhxbuk"/><path class="ay2f4rb_p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:baseball-base" {...props}></Icon>
<style>
:global(.ay2f4rb_p) {
  d: path("M2.5 11v3l9.5 5l9.5-5v-3M12 16v3");
}

:global(.cwhhhxbuk) {
  d: path("m5.022 9.673l6.279-3.305a1.5 1.5 0 0 1 1.398 0l6.279 3.305a1.5 1.5 0 0 1 0 2.654l-6.279 3.305a1.5 1.5 0 0 1-1.398 0l-6.279-3.305a1.5 1.5 0 0 1 0-2.654");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
