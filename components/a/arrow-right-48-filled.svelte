<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cbb-664ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-right-48-filled" {...props}></Icon>
<style>
:global(.cbb-664ne) {
  fill: currentColor;
  d: path("M3.75 24a1.5 1.5 0 0 1 1.5-1.5h31.835L24.698 10.32a1.5 1.5 0 1 1 2.104-2.14l14.997 14.748l.009.009l.011.011a1.5 1.5 0 0 1-.042 2.145L26.802 39.82a1.5 1.5 0 1 1-2.104-2.139L37.085 25.5H5.25a1.5 1.5 0 0 1-1.5-1.5");
}

</style>
