<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cojuvgxvn"/><path class="poa4r25xv"/><path class="wddphhbzi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:git-merge-line-duotone" {...props}></Icon>
<style>
:global(.cojuvgxvn) {
  d: path("M5 22V8C5 14.5 9.5 19 16 19");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.poa4r25xv) {
  d: path("M8 5C8 6.6569 6.6569 8 5 8C3.3431 8 2 6.6569 2 5C2 3.3431 3.3431 2 5 2C6.6569 2 8 3.3431 8 5Z");
}

:global(.wddphhbzi) {
  d: path("M22 19C22 20.6569 20.6569 22 19 22C17.3431 22 16 20.6569 16 19C16 17.3431 17.3431 16 19 16C20.6569 16 22 17.3431 22 19Z");
}

</style>
