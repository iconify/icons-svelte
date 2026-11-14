<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2dqx08qj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:heading-4" {...props}></Icon>
<style>
:global(.l2dqx08qj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 5v14m8-14v14m-8-7h8m7.75 7V9l-4 6.75H21");
}

</style>
