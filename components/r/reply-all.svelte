<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="md9o1691n"/><path class="z_qzmiqfi"/><path class="u8p78jm5t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:reply-all" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.md9o1691n) {
  d: path("M8 11h6.5a5 5 0 0 1 5 5v3");
}

:global(.u8p78jm5t) {
  d: path("m8.5 6l-5 5l5 5");
}

:global(.z_qzmiqfi) {
  d: path("m13 6l-5 5l5 5");
}

</style>
