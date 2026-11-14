<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ram8qib6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:air-gasper" {...props}></Icon>
<style>
:global(.ram8qib6l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5V5m-6 6a6 6 0 0 1 12 0Zm2 2.75q-1 2 0 4t0 3.75m4-7.75q-1 2 0 4t0 3.75m4-7.75q-1 2 0 4t0 3.75");
}

</style>
