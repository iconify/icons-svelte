<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifm6szudy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pay-equity" {...props}></Icon>
<style>
:global(.ifm6szudy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM3.5 7h17M12 7v13.5m-3.5 0h7M5.5 7v6M2 13h7a3.5 3.5 0 0 1-7 0Zm16.5-6v6M15 13h7a3.5 3.5 0 0 1-7 0Z");
}

</style>
