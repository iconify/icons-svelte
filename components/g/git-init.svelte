<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvyjnybpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:git-init" {...props}></Icon>
<style>
:global(.lvyjnybpy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 11a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M10 2.5v5m0 7v7m8-6.5v6m-3-3h6");
}

</style>
