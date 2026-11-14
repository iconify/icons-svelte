<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w01vqrgfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:percent" {...props}></Icon>
<style>
:global(.w01vqrgfg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 18.5l13-13M4.5 7a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m10 10a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
