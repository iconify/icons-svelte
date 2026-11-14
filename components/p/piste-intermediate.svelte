<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="choom_b0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:piste-intermediate" {...props}></Icon>
<style>
:global(.choom_b0i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 2.5h8A3.5 3.5 0 0 1 19.5 6v7a3.5 3.5 0 0 1-3.5 3.5H8A3.5 3.5 0 0 1 4.5 13V6A3.5 3.5 0 0 1 8 2.5m4 14v5M7.25 5.25l9.5 8.5");
}

</style>
