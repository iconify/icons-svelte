<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cirgusbhj"/><path class="ntc2gpbtp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:power-restart" {...props}></Icon>
<style>
:global(.cirgusbhj) {
  d: path("M17.142 6.872a8 8 0 1 1-10.284 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ntc2gpbtp) {
  d: path("M3.75 6.75h3v3M12 3v8");
}

</style>
