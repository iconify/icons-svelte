<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="o_yttac8f"/><path class="hjxtt2cfv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:procurement" {...props}></Icon>
<style>
:global(.hjxtt2cfv) {
  d: path("M3.75 13.5h16.5M12 2.75V6.5M9.75 4.25L12 6.5l2.25-2.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o_yttac8f) {
  width: 16.5px;
  height: 11.75px;
  x: 3.75px;
  y: 9.5px;
  rx: 2px;
}

</style>
