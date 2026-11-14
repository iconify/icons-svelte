<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnif4hblg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:desk" {...props}></Icon>
<style>
:global(.jnif4hblg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6h19M5 6v13m7-13v13h8.5V6M12 11.5h8.5m-5.75-2.75h3");
}

</style>
