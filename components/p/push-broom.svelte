<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_4z1p05e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:push-broom" {...props}></Icon>
<style>
:global(.n_4z1p05e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 14h14.5A1.75 1.75 0 0 1 21 15.75a1.75 1.75 0 0 1-1.75 1.75H4.75A1.75 1.75 0 0 1 3 15.75A1.75 1.75 0 0 1 4.75 14M12 14l5.5-11.5M6 17.5V21m4-3.5V21m4-3.5V21m4-3.5V21");
}

</style>
