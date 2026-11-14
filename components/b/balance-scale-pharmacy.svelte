<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhfgq7bop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:balance-scale-pharmacy" {...props}></Icon>
<style>
:global(.dhfgq7bop) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 7h15M12 4v16.5m-4 0h8M3 13a3 3 0 0 0 6 0Zm12 0a3 3 0 0 0 6 0ZM6 7l-3 6m3-6l3 6m9-6l-3 6m3-6l3 6");
}

</style>
