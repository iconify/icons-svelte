<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xpf-gg0uu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:risk-level-low" {...props}></Icon>
<style>
:global(.xpf-gg0uu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16.5a9.5 9.5 0 0 1 19 0m-9.5 0L6 14m6 2.5h.01");
}

</style>
