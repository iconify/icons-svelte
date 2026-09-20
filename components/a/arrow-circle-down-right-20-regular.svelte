<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jlgmt2bce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-circle-down-right-20-regular" {...props}></Icon>
<style>
:global(.jlgmt2bce) {
  fill: currentColor;
  d: path("M12.851 12.856A.5.5 0 0 1 12.5 13h-5a.5.5 0 0 1 0-1h3.793L7.146 7.854a.5.5 0 1 1 .708-.708L12 11.293V7.5a.5.5 0 0 1 1 0v5a.5.5 0 0 1-.144.351zM10 18a8 8 0 1 0 0-16a8 8 0 0 0 0 16m7-8a7 7 0 1 1-14 0a7 7 0 0 1 14 0");
}

</style>
