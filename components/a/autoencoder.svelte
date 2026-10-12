<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lxej1m1pi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:autoencoder" {...props}></Icon>
<style>
:global(.lxej1m1pi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.56 3.84l4.88 3.57Q9.25 8 9.25 9v6q0 1-.81 1.59l-4.88 3.57q-.81.59-.81-.41V4.25q0-1 .81-.41m17.69.41v15.5q0 1-.81.41l-4.88-3.57q-.81-.59-.81-1.59V9q0-1 .81-1.59l4.88-3.57q.81-.59.81.41M12 10v4");
}

</style>
