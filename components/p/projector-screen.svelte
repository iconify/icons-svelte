<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7pcdhb9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:projector-screen" {...props}></Icon>
<style>
:global(.x7pcdhb9p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h19M4 3.5V15a1.5 1.5 0 0 0 1.5 1.5h13A1.5 1.5 0 0 0 20 15V3.5m-8 13v4");
}

</style>
