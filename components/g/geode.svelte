<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hzeeagn7b"/><path class="cyqjnmbaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:geode" {...props}></Icon>
<style>
:global(.cyqjnmbaj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.8 22.339L24 13.475l12.2 8.864l-4.66 14.342H16.46");
}

:global(.hzeeagn7b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.683L3.689 19.44l7.758 23.877h25.106l7.758-23.877");
}

</style>
