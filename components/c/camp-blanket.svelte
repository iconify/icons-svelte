<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bsoyd5b1r"/><path class="k2j_68bqp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:camp-blanket" {...props}></Icon>
<style>
:global(.bsoyd5b1r) {
  d: path("M5.5 5h12L21 8.5V11H5.5a3 3 0 0 1 0-6m0 8.75H21v6H5.5a3 3 0 0 1 0-6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k2j_68bqp) {
  d: path("M17.5 5v3.5H21M14 5v6m0 2.75v6");
}

</style>
