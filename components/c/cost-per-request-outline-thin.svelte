<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bqn9n10jh"/><path class="u514_sb-x"/><path class="g45cwl_by"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cost-per-request-outline-thin" {...props}></Icon>
<style>
:global(.bqn9n10jh) {
  d: path("M3 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.g45cwl_by) {
  d: path("M12 17a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.u514_sb-x) {
  d: path("m8 8 6 6");
}

</style>
