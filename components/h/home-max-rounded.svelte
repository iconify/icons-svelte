<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ef83klnyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:home-max-rounded" {...props}></Icon>
<style>
:global(.ef83klnyh) {
  fill: currentColor;
  d: path("M8 18H5.5q-1.458 0-2.479-1.021T2 14.5v-5q0-1.458 1.021-2.479T5.5 6h13q1.458 0 2.479 1.021T22 9.5v5q0 1.458-1.021 2.479T18.5 18H16q0 .31-.23.54t-.54.23H8.77q-.31 0-.54-.23T8 18");
}

</style>
