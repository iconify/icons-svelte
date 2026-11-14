<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6jb0gd2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:clt-panel" {...props}></Icon>
<style>
:global(.x6jb0gd2q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 4h12a3.5 3.5 0 0 1 3.5 3.5v9A3.5 3.5 0 0 1 18 20H6a3.5 3.5 0 0 1-3.5-3.5v-9A3.5 3.5 0 0 1 6 4M2.5 9.5h19m-19 5h19M8.75 4v5.5m6.5-5.5v5.5m-3.25 5V20");
}

</style>
