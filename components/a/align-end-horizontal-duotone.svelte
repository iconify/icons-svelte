<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="o8bqm2lzu"/><path class="qx17hvbxe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:align-end-horizontal-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.o8bqm2lzu) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 1C9.6569 1 11 2.343 11 4V16C11 17.657 9.6568 19 8 19H6C4.3432 19 3 17.657 3 16V4C3 2.343 4.3431 1 6 1H8ZM18 9C19.6569 9 21 10.343 21 12V16C21 17.657 19.6569 19 18 19H16C14.3431 19 13 17.657 13 16V12C13 10.343 14.3431 9 16 9H18Z");
}

:global(.qx17hvbxe) {
  d: path("M22 21C22.5523 21 23 21.448 23 22C23 22.552 22.5523 23 22 23H2C1.4477 23 1 22.552 1 22C1 21.448 1.4477 21 2 21H22Z");
}

</style>
