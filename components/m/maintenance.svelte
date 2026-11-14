<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f1a4s5htp"/><path class="pe1cgjgca"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:maintenance" {...props}></Icon>
<style>
:global(.f1a4s5htp) {
  d: path("M16.781 3.568a4.5 4.5 0 1 1-5.213 3.651");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pe1cgjgca) {
  d: path("M13.066 10.934za1.75 1.75 0 0 1 0 2.475l-5.657 5.657a1.75 1.75 0 0 1-2.475 0a1.75 1.75 0 0 1 0-2.475l5.657-5.657a1.75 1.75 0 0 1 2.475 0");
}

</style>
