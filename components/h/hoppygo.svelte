<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ufeya9lej"/><path class="lu3igqupx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:hoppygo" {...props}></Icon>
<style>
:global(.lu3igqupx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.668 45.332C15.42 46.737 5.013 39.168 2.885 28.034S7.639 6.027 18.612 3.184m3.83-.631c10.89-.76 20.621 6.76 22.63 17.49s-4.34 21.262-14.767 24.494");
}

:global(.ufeya9lej) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.385 44.86c-2.265-16.333-1.88-25.909-1.142-29.03c2.341-9.531 14.6-2.501 9.248 3.617c-4.963 4.747-20.846 3.718-24.085 7.044c-8.15 8.287 8.397 16.402 8.745 1.841c.189-9.223.745-17.369-.698-25.53");
}

</style>
