<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="r7ku0ubav"/><circle class="etycyt-mg"/><circle class="eccs3wb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:divide" {...props}></Icon>
<style>
:global(.eccs3wb1i) {
  cx: 18px;
  cy: 29px;
  r: 4px;
  fill: var(--svg-color--31373d, #31373d);
}

:global(.etycyt-mg) {
  cx: 18px;
  cy: 7px;
  r: 4px;
  fill: var(--svg-color--31373d, #31373d);
}

:global(.r7ku0ubav) {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M34 18a3 3 0 0 1-3 3H5a3 3 0 1 1 0-6h26a3 3 0 0 1 3 3");
}

</style>
