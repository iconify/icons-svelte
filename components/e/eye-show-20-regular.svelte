<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="a_yz_3bgn"/><path class="lj9b8l4qj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:eye-show-20-regular" {...props}></Icon>
<style>
:global(.a_yz_3bgn) {
  d: path("M3.26 11.602C3.942 8.327 6.793 6 10 6c3.206 0 6.057 2.327 6.74 5.602a.5.5 0 0 0 .98-.204C16.943 7.673 13.693 5 10 5c-3.693 0-6.943 2.673-7.72 6.398a.5.5 0 0 0 .98.204z");
  fill: currentColor;
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.lj9b8l4qj) {
  d: path("M10 8a3.5 3.5 0 1 0 0 7a3.5 3.5 0 0 0 0-7zm-2.5 3.5a2.5 2.5 0 1 1 5 0a2.5 2.5 0 0 1-5 0z");
  fill: currentColor;
}

</style>
