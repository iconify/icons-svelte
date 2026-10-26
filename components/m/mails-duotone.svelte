<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cjqzv2bst"/><path class="bgiipv7ny"/><path class="ua6hv8b8w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:mails-duotone" {...props}></Icon>
<style>
:global(.bgiipv7ny) {
  stroke-opacity: 0.4;
  d: path("M2 13L2 7C2 5.3431 3.3431 4 5 4L15 4");
}

:global(.cjqzv2bst) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 7L19 7C21.2092 7 23 8.7908 23 11L23 17C23 19.2092 21.2092 21 19 21L9 21C6.7908 21 5 19.2092 5 17L5 11C5 8.7908 6.7908 7 9 7Z");
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ua6hv8b8w) {
  d: path("M6 11L13.6046 14.2733C13.857 14.3819 14.143 14.3819 14.3954 14.2733L22 11");
}

</style>
