<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yeip2-y6i"/><path class="ar_zf9d2w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:alert-fill" {...props}></Icon>
<style>
:global(.ar_zf9d2w) {
  fill: currentColor;
  d: path("M13 19C13 19.55228 12.55228 20 12 20C11.44772 20 11 19.55228 11 19C11 18.44772 11.44772 18 12 18C12.55228 18 13 18.44772 13 19Z");
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.yeip2-y6i) {
  d: path("M12 5V15");
}

</style>
