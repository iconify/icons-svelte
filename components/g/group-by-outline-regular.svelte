<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ybh1xwgpp"/><path class="qfe94rk-q"/><path class="ygvoi9umd"/><path class="hxoe7gx5p"/><path class="vox58lg-w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:group-by-outline-regular" {...props}></Icon>
<style>
:global(.hxoe7gx5p) {
  d: path("M12 5v12");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qfe94rk-q) {
  d: path("M2 11h8");
}

:global(.vox58lg-w) {
  d: path("M12 11h10");
}

:global(.ybh1xwgpp) {
  d: path("M2 5h8");
}

:global(.ygvoi9umd) {
  d: path("M2 17h8");
}

</style>
