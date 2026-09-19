<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fqct5pbki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:a17track" {...props}></Icon>
<style>
:global(.fqct5pbki) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m40.602 24.617l-6.735 12.516h6.735ZM8.219 14.443l6.566-3.576m0 0v26.266m11.541 0l14.133-26.266H23.058");
}

</style>
