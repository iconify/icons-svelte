<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zumgck-rj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:notepad" {...props}></Icon>
<style>
:global(.zumgck-rj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.06 7.45S6.14 30.77 4.5 40.55h39l-6.59-33Zm3.11 6.41h21.66m-22.86 6.66h24.06m-25.31 6.74h26.56M9.6 34.19h28.8");
}

</style>
