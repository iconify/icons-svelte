<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="abnm6smsv"/><path class="a5uqb5btg"/><path class="r-3ib9fxz"/><path class="i4l6z3b8k"/><path class="l1jjkky7x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:report-outline-regular" {...props}></Icon>
<style>
:global(.a5uqb5btg) {
  d: path("M9 14v4");
}

:global(.abnm6smsv) {
  d: path("M13 3H6v18h12V8");
}

:global(.i4l6z3b8k) {
  d: path("M15 13v5");
}

:global(.l1jjkky7x) {
  d: path("M8 18h8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r-3ib9fxz) {
  d: path("M12 11v7");
}

</style>
