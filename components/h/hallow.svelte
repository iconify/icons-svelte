<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="fdsqkbb7k"/><path class="sivznz7oy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:hallow" {...props}></Icon>
<style>
:global(.fdsqkbb7k) {
  cx: 24px;
  cy: 27.813px;
  r: 15.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.sivznz7oy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.95 5.836c.079 1.043-5.655 2.327-12.807 2.867s-13.014.134-13.093-.91c-.079-1.043 5.655-2.327 12.807-2.867s13.014-.133 13.093.91");
}

</style>
