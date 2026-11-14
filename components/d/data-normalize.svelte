<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0i_iv5-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:data-normalize" {...props}></Icon>
<style>
:global(.b0i_iv5-k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5v17h17M6.5 7h13m-11 0v10.5m4-10.5v7m4-7v4");
}

</style>
