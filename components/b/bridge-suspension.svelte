<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnp-l7bux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bridge-suspension" {...props}></Icon>
<style>
:global(.jnp-l7bux) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14h19M6.5 4v17m11-17v17M2.5 8l4 6m0-9c3.5 8 7.5 8 11 0m0 9l4-6");
}

</style>
