<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="f-2qe-b0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:currency-ngn-bold" {...props}></Icon>
<style>
:global(.f-2qe-b0b) {
  fill: currentColor;
  d: path("M216 116h-12V46a12 12 0 0 0-24 0v70h-46.14l-60.4-77.38A12 12 0 0 0 52 46v70H40a12 12 0 0 0 0 24h12v70a12 12 0 0 0 24 0v-70h46.14l60.4 77.38A12 12 0 0 0 204 210v-70h12a12 12 0 0 0 0-24m-140 0V80.88L103.41 116Zm104 59.12L152.59 140H180Z");
}

</style>
