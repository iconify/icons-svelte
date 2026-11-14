<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tkaq1tbgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:code-commit" {...props}></Icon>
<style>
:global(.tkaq1tbgl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h6m7 0h6m-13 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

</style>
