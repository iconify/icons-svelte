<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="krbimdb8o"/><rect class="opwd1ab7b"/><path class="qvsb4-9gz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:legal-aid" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.krbimdb8o) {
  d: path("M12 3v6.5m-3.75-5h7.5m-7.5 0L6.75 8a1.5 1.5 0 0 0 3 0Zm7.5 0L14.25 8a1.5 1.5 0 0 0 3 0Z");
}

:global(.opwd1ab7b) {
  width: 2.5px;
  height: 7.75px;
  x: 2.75px;
  y: 13.5px;
  rx: 1px;
}

:global(.qvsb4-9gz) {
  d: path("M5.25 14.5H8l3.5 1.5h2a1.25 1.25 0 0 1 0 2.5h-3M5.25 21H14l6-3.25a1.25 1.25 0 0 0-1.25-2.15l-3.25 1.15");
}

</style>
