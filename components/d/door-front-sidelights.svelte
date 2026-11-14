<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f093fvbyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:door-front-sidelights" {...props}></Icon>
<style>
:global(.f093fvbyo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.5h14.5A1.75 1.75 0 0 1 21 4.25v15.5a1.75 1.75 0 0 1-1.75 1.75H4.75A1.75 1.75 0 0 1 3 19.75V4.25A1.75 1.75 0 0 1 4.75 2.5m2.75 0v19m9-19v19M13.75 12h.01");
}

</style>
