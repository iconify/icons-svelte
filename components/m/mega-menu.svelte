<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qypfk4xvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mega-menu" {...props}></Icon>
<style>
:global(.qypfk4xvw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.5h14.5a2.25 2.25 0 0 1 2.25 2.25A2.25 2.25 0 0 1 19.25 7H4.75A2.25 2.25 0 0 1 2.5 4.75A2.25 2.25 0 0 1 4.75 2.5M6 10h12a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 18v-4.5A3.5 3.5 0 0 1 6 10m1.5 3.25v5m4.5-5v5m4.5-5v5");
}

</style>
