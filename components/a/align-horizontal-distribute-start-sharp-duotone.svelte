<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rilsb3btw"/><path class="aizxn2byf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:align-horizontal-distribute-start-sharp-duotone" {...props}></Icon>
<style>
:global(.aizxn2byf) {
  d: path("M5 1V23H3V1H5ZM15 1V23H13V1H15Z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.rilsb3btw) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 3C10.552 3 11 3.448 11 4V20C11 20.552 10.552 21 10 21H4C3.448 21 3 20.552 3 20V4C3 3.448 3.448 3 4 3H10ZM20 7C20.552 7 21 7.448 21 8V16C21 16.552 20.552 17 20 17H14C13.448 17 13 16.552 13 16V8C13 7.448 13.448 7 14 7H20Z");
}

</style>
