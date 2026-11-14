<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4lwhn9uz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:black-ice" {...props}></Icon>
<style>
:global(.m4lwhn9uz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21.5L9.5 4m8.262 8.782L14.5 4M12 8.5v6m6.5 1v6M16 17l5 3m-5 0l5-3");
}

</style>
