<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m1hvpgy4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:haven" {...props}></Icon>
<style>
:global(.m1hvpgy4f) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.392 24L4.5 10.087M24.392 24L4.5 37.913m25.572-2.796H43.5");
}

</style>
