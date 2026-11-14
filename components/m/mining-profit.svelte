<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4f148bqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mining-profit" {...props}></Icon>
<style>
:global(.h4f148bqz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5V21h18M8 17.5V15m4.75 2.5v-5m4.75 5V11M15 5.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
