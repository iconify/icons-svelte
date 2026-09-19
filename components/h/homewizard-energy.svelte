<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ye5ag5bzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:homewizard-energy" {...props}></Icon>
<style>
:global(.ye5ag5bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.92 38.382h10.218m-5.108-5.109V43.49m-19.692.01L37.14 18.698H25.76L36.903 4.5H24.33c-1.25 0-2.405.667-3.03 1.75L10.86 24.333h8.94z");
}

</style>
