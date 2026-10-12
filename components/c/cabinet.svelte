<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="t3yejqb7x"/><path class="s-htnoz9k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cabinet" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s-htnoz9k) {
  d: path("M2.75 9h18.5M12 9v10.25M10.5 6.6h3m-4 5.4v2.5m5-2.5v2.5M6 19.25v2m12-2v2");
}

:global(.t3yejqb7x) {
  width: 18.5px;
  height: 15px;
  x: 2.75px;
  y: 4.25px;
  rx: 2px;
}

</style>
