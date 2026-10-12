<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v_7knkbwn"/><circle class="lygk6dbzl"/><path class="zvaizmb1y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:magic-staff" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lygk6dbzl) {
  cx: 16.5px;
  cy: 7.5px;
  r: 3px;
}

:global(.v_7knkbwn) {
  d: path("M3.75 20.25L14.38 9.62");
}

:global(.zvaizmb1y) {
  d: path("M7 4q.3 2.2 2.5 2.5Q7.3 6.8 7 9q-.3-2.2-2.5-2.5Q6.7 6.2 7 4");
}

</style>
