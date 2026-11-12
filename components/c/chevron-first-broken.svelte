<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nzhoqcmml"/><path class="v9gqdsvmm"/><path class="cfxd4se9w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chevron-first-broken" {...props}></Icon>
<style>
:global(.cfxd4se9w) {
  d: path("M7.5 5L7.49998 19.0004");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nzhoqcmml) {
  stroke-linejoin: round;
  d: path("M12 10.25L10.5 12L16.5 19");
}

:global(.v9gqdsvmm) {
  d: path("M15 6.75L16.5 5");
}

</style>
