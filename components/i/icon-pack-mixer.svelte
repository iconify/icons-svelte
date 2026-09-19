<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w664sw2vy"/><path class="houtgjb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:icon-pack-mixer" {...props}></Icon>
<style>
:global(.houtgjb6a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.423 10.985c2.573 7.942 8.492 26.03 14.585 26.03c7.43 0 14.492-7.477 14.492-7.477");
}

:global(.w664sw2vy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 28.338c0 3.739.6 8.677 3.646 8.677c4.8 0 10.477-16.661 26.954-25.477");
}

</style>
