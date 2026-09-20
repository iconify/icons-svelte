<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="o2boujbbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:map-pin-simple-line-thin" {...props}></Icon>
<style>
:global(.o2boujbbo) {
  fill: currentColor;
  d: path("M216 212h-84v-80.17a52 52 0 1 0-8 0V212H40a4 4 0 0 0 0 8h176a4 4 0 0 0 0-8M84 80a44 44 0 1 1 44 44a44.05 44.05 0 0 1-44-44");
}

</style>
