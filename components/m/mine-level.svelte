<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_2otlbkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mine-level" {...props}></Icon>
<style>
:global(.t_2otlbkz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 3h15M12 3v18.5M12 8h7M5 13.5h7m0 5.5h7");
}

</style>
