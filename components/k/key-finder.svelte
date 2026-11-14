<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrnbanb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:key-finder" {...props}></Icon>
<style>
:global(.qrnbanb-b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 8a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m10.25-4.75a7.5 7.5 0 0 1 0 9.5m-11.5 0a7.5 7.5 0 0 1 0-9.5M12 12.5v9m0-4h2.5m-2.5 3h3");
}

</style>
