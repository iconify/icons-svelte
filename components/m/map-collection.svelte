<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hkoqnyrzh"/><path class="q4kykgc9i"/><path class="tmucf2bze"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:map-collection" {...props}></Icon>
<style>
:global(.hkoqnyrzh) {
  d: path("m2.5 10l4.25-1.5l4.5 1.5l4.25-1.5V20l-4.25 1.5l-4.5-1.5l-4.25 1.5Zm4.25-1.5V20m4.5-10v11.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q4kykgc9i) {
  d: path("m5.5 7l4.25-1.5l4.5 1.5l4.25-1.5V17l-3 1");
}

:global(.tmucf2bze) {
  d: path("m8.5 4l4.25-1.5l4.5 1.5l4.25-1.5V14l-3 1");
}

</style>
