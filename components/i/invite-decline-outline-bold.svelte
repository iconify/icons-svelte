<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="u9zbhwwpi"/><path class="er-rmmbme"/><path class="i-eao3sns"/><path class="b3d1hobxs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:invite-decline-outline-bold" {...props}></Icon>
<style>
:global(.b3d1hobxs) {
  d: path("m22 13 -4 4");
}

:global(.er-rmmbme) {
  d: path("M6 10V5h6v5");
}

:global(.i-eao3sns) {
  d: path("m18 13 4 4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u9zbhwwpi) {
  d: path("M2 10v9h14v-9Z");
}

</style>
