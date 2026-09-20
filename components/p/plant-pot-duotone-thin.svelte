<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sct3_2bnu"/><path class="ke0fmmbat"/><path class="czq8efv3e"/><path class="wlp3ibbib"/><path class="zzohglbtd"/><path class="luzt4cbce"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:plant-pot-duotone-thin" {...props}></Icon>
<style>
:global(.czq8efv3e) {
  d: path("M8 13v8h8v-8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ke0fmmbat) {
  fill: currentColor;
  d: path("M12 13c0 -3 3 -6 6 -7 0 3 -2 6 -6 7");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.luzt4cbce) {
  d: path("M12 13c0 -3 3 -6 6 -7 0 3 -2 6 -6 7");
}

:global(.sct3_2bnu) {
  fill: currentColor;
  d: path("M12 13c0 -4 -3 -7 -6 -8 0 4 2 7 6 8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wlp3ibbib) {
  d: path("M6 13h12");
}

:global(.zzohglbtd) {
  d: path("M12 13c0 -4 -3 -7 -6 -8 0 4 2 7 6 8");
}

</style>
