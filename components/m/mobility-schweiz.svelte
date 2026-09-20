<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l7f2occgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mobility-schweiz" {...props}></Icon>
<style>
:global(.l7f2occgz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.764 21.362a8.118 8.118 0 1 1 16.236 0v13.395M7.764 13.243v21.514M24 21.362a8.118 8.118 0 1 1 16.236 0v13.395m-35.736 0h6.527M4.5 13.451l3.264-.208m12.972 21.514h6.528m9.709 0H43.5");
}

</style>
