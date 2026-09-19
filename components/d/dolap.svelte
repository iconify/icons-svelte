<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ve1fx3bai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:dolap" {...props}></Icon>
<style>
:global(.ve1fx3bai) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.18 14.817v24.585c.118 3.91-2.587 5.816-6.141 2.093l-14.45-14.28c-.946-.934-.959-2.355.369-3.667L27.674 5.051c.969-.773 1.992-.709 2.945.044l8.658 8.487c1.198 1.238.935 2.054.045 2.982l-10.076 9.942");
}

</style>
