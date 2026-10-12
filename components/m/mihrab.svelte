<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="wkg5_f5aq"/><path class="avgh_-bpf"/><path class="w0-28b8kv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:mihrab" {...props}></Icon>
<style>
:global(.avgh_-bpf) {
  d: path("M7.75 21V11c0-2.5 1.75-4.5 4.25-6.25C14.5 6.5 16.25 8.5 16.25 11v10M12 8.75V11");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w0-28b8kv) {
  d: path("M10.25 11h3.5l-1 2.75h-1.5Z");
}

:global(.wkg5_f5aq) {
  width: 16.5px;
  height: 18.5px;
  x: 3.75px;
  y: 2.75px;
  rx: 1.5px;
}

</style>
