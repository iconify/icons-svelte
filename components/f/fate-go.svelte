<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r9mvvpbbw"/><path class="xk6v1sbnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:fate-go" {...props}></Icon>
<style>
:global(.r9mvvpbbw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.544 9.044L24 3.5L10.333 17.167L24 30.833l13.667-13.666l-5.545-5.545");
}

:global(.xk6v1sbnn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 17.166l13.667 13.667L24 44.5L10.333 30.833zm7.198-4.62l1.848-1.848");
}

</style>
