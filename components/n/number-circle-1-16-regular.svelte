<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m41qo5gul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:number-circle-1-16-regular" {...props}></Icon>
<style>
:global(.m41qo5gul) {
  fill: currentColor;
  d: path("M8 2a6 6 0 1 0 0 12A6 6 0 0 0 8 2M1 8a7 7 0 1 1 14 0A7 7 0 0 1 1 8m7.554-3.247A.5.5 0 0 1 9 5.25v5.25a.5.5 0 0 1-1 0V6.986a3.6 3.6 0 0 1-1.043.72a.5.5 0 1 1-.414-.911a2.7 2.7 0 0 0 1.174-1.046a3 3 0 0 0 .3-.628v-.005a.5.5 0 0 1 .537-.363");
}

</style>
