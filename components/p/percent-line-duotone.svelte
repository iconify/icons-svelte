<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oqdxdpjwb"/><path class="k3j03ybqs"/><path class="qpu-dbcnd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:percent-line-duotone" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k3j03ybqs) {
  d: path("M9 6.5C9 7.8807 7.8807 9 6.5 9C5.1193 9 4 7.8807 4 6.5C4 5.1193 5.1193 4 6.5 4C7.8807 4 9 5.1193 9 6.5Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.oqdxdpjwb) {
  d: path("M19 5L5 19");
}

:global(.qpu-dbcnd) {
  d: path("M20 17.5C20 18.8807 18.8807 20 17.5 20C16.1193 20 15 18.8807 15 17.5C15 16.1193 16.1193 15 17.5 15C18.8807 15 20 16.1193 20 17.5Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
