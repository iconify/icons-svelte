<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ap150qvgk"/><path class="jhpk65hie"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:discount-amount" {...props}></Icon>
<style>
:global(.ap150qvgk) {
  d: path("M5.125 2.5h4.788a2.63 2.63 0 0 1 1.856.769l7.625 7.625a2.625 2.625 0 0 1 0 3.712l-4.788 4.788a2.625 2.625 0 0 1-3.712 0l-7.625-7.625A2.63 2.63 0 0 1 2.5 9.913V5.125A2.625 2.625 0 0 1 5.125 2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jhpk65hie) {
  d: path("M5.25 6.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M10 13.5h5.5");
}

</style>
