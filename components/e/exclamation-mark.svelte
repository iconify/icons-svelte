<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="x_h1v4jih"/><ellipse class="xu957cb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:exclamation-mark" {...props}></Icon>
<style>
:global(.x_h1v4jih) {
  fill: currentColor;
  d: path("M36.989 42.439H27.01L23 2h18z");
}

:global(.xu957cb6b) {
  cx: 31.999px;
  cy: 54.354px;
  fill: currentColor;
  rx: 7.663px;
  ry: 7.646px;
}

</style>
