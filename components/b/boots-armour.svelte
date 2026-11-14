<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnyuw0bhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:boots-armour" {...props}></Icon>
<style>
:global(.mnyuw0bhx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 6.5V3h9v3.5m-9 4V21h15v-4a3 3 0 0 0-2-2.75l-4-1.75v-2M4 6.5h12v4H4Z");
}

</style>
