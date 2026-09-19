<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z5_yrfbti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:rocketbook" {...props}></Icon>
<style>
:global(.z5_yrfbti) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 29.13V43.5m-4.51-14.37v9.77m15.1-9.77L24 4.5L13.41 29.13m15.1 0v9.77");
}

</style>
