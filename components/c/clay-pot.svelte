<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tlqzxntgy"/><path class="whn4d5n3f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:clay-pot" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tlqzxntgy) {
  d: path("M3.5 9.75h17m-15.75 3h14.5a.75.75 0 0 1 .75.8c-.5 4.4-3.6 7.7-8 7.7s-7.5-3.3-8-7.7a.75.75 0 0 1 .75-.8");
}

:global(.whn4d5n3f) {
  d: path("M6.75 15.75q5.25 1.5 10.5 0");
}

</style>
