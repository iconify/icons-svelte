<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hbepmkbah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:leaf-needle" {...props}></Icon>
<style>
:global(.hbepmkbah) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 15v6.5m0-6.5L4.5 4.5M12 15L9.5 2.5M12 15l2.5-12.5M12 15l7.5-10.5");
}

</style>
