<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ph4toqkti"/><path class="s7h04rdua"/><path class="qxwxnhbhy"/><path class="yfo1v5ftn"/><path class="l91vssbqw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:exact-search-duotone-regular" {...props}></Icon>
<style>
:global(.l91vssbqw) {
  d: path("M15 21h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ph4toqkti) {
  fill: currentColor;
  d: path("M4 9a5 5 0 1 0 10 0A5 5 0 1 0 4 9");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.qxwxnhbhy) {
  d: path("M12.5 12.5 16 16");
}

:global(.s7h04rdua) {
  d: path("M4 9a5 5 0 1 0 10 0A5 5 0 1 0 4 9");
}

:global(.yfo1v5ftn) {
  d: path("M15 17.5h6");
}

</style>
