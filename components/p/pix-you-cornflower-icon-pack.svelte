<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oj464bbcb"/><path class="ab9g42bke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:pix-you-cornflower-icon-pack" {...props}></Icon>
<style>
:global(.ab9g42bke) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.397 38.558l7.103 2.621L30.167 6.821L24 24");
}

:global(.oj464bbcb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.064 38.558l7.103 2.621L17.833 6.821L5.5 41.179l7.103-2.621");
}

</style>
