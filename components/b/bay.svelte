<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="td_h78bej"/><path class="f8_n3-btd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bay" {...props}></Icon>
<style>
:global(.f8_n3-btd) {
  d: path("M14.5 12c.83-.6 1.67-.6 2.5 0s1.67.6 2.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.td_h78bej) {
  d: path("M2.75 2.75H12c3 0 6.5 1.75 7.5 4c-3.5-.25-8 1.25-8 5.25c0 3.5 4 5.25 9.75 5v4.25H2.75Z");
}

</style>
