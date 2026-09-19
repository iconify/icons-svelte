<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t_mc8qfgi"/><path class="a4uboobxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:didi-greater-china" {...props}></Icon>
<style>
:global(.a4uboobxz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.22 15.877c-.448 7.107-.36 13.794 6.82 15.534");
}

:global(.t_mc8qfgi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.805 8.3H36.36v7.306h6.55s4.255 17.342-10.068 22.19c-9.568 3.24-16.858 2.367-22.516-2.76C2.918 28.325 4.602 8.224 4.805 8.3");
}

</style>
