<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h_lb8vbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:pant" {...props}></Icon>
<style>
:global(.h_lb8vbqs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.42 34.816c-13.527-9.872-.914-23.763 8.47-23.032m-.899 6.439l12.734-6.094l-10.662-5.788zm19.589-5.039c13.527 9.872.914 23.764-8.47 23.032m.899-6.439l-12.734 6.094l10.662 5.788z");
}

</style>
