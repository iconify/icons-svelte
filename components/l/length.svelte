<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxacliw7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:length" {...props}></Icon>
<style>
:global(.zxacliw7p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h19m-19-4.5v9m19-9v9M5.5 9l-3 3l3 3m13-6l3 3l-3 3");
}

</style>
