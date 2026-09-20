<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k6nj2fbya"/><path class="bg2ejdbaq"/><path class="b1ja9gnou"/><path class="z0kumyy5w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:double-entry-outline-regular" {...props}></Icon>
<style>
:global(.b1ja9gnou) {
  d: path("M5 10h4.5");
}

:global(.bg2ejdbaq) {
  d: path("M12 5v16");
}

:global(.k6nj2fbya) {
  d: path("M3 5h18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.z0kumyy5w) {
  d: path("M14.5 14H19");
}

</style>
