<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="abnm6smsv"/><path class="lhfoj2bfk"/><path class="o7-7k5bqs"/><path class="zpdz8rbaf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:response-body-outline-thin" {...props}></Icon>
<style>
:global(.abnm6smsv) {
  d: path("M13 3H6v18h12V8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lhfoj2bfk) {
  d: path("M12 6v4.5");
}

:global(.o7-7k5bqs) {
  d: path("M9.5 8.5 12 6l2.5 2.5");
}

:global(.zpdz8rbaf) {
  d: path("M9 15.5h6");
}

</style>
