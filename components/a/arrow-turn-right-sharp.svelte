<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ehg_xi53w"/><path class="fdk2_9u8w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:arrow-turn-right-sharp" {...props}></Icon>
<style>
:global(.ehg_xi53w) {
  d: path("M5.25 20.25v-6.5a5 5 0 0 1 5-5h9.5");
}

:global(.fdk2_9u8w) {
  d: path("m15.75 4.75l4 4l-4 4");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
