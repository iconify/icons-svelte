<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e8ntogbjc"/><path class="f7sduabpt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:neutron" {...props}></Icon>
<style>
:global(.e8ntogbjc) {
  d: path("M4.75 4.75a10.25 4.5 45 1 1 14.5 14.5a10.25 4.5 45 1 1-14.5-14.5");
}

:global(.f7sduabpt) {
  d: path("M4.75 19.25a10.25 4.5-45 1 1 14.5-14.5a10.25 4.5-45 1 1-14.5 14.5M12 12h.01");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
