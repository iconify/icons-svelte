<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="xnw6rezjr"/><path class="a8kdvk-nl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:return-box" {...props}></Icon>
<style>
:global(.a8kdvk-nl) {
  d: path("M3.25 14.25h17.5m-10-3.5v3.5h2.5v-3.5m4-2.5v-.5a2.5 2.5 0 0 0-2.5-2.5h-9.5m2.5-2.5l-2.5 2.5l2.5 2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xnw6rezjr) {
  width: 17.5px;
  height: 10.5px;
  x: 3.25px;
  y: 10.75px;
  rx: 2px;
}

</style>
