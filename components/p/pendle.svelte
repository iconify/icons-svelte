<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="porvbcb6j"/><path class="xdxzkhn3s"/><path class="d4xkbclai"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:pendle" {...props}></Icon>
<style>
:global(.d4xkbclai) {
  fill: var(--svg-color--152e51, #152e51);
  d: path("M8.326 4.007v10.017h.883V3.56q-.459.194-.883.446");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.porvbcb6j) {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.2 10.2a7.2 7.2 0 1 1-14.4 0a7.2 7.2 0 0 1 14.4 0");
}

:global(.xdxzkhn3s) {
  fill: var(--svg-color--152e51, #152e51);
  d: path("M8.76 21a3.961 3.961 0 1 0 .001-7.922a3.961 3.961 0 0 0 0 7.922");
}

</style>
