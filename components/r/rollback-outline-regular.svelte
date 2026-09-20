<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zt9xgrbcr"/><path class="uvgrx_yvv"/><path class="f4naz_w9a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rollback-outline-regular" {...props}></Icon>
<style>
:global(.f4naz_w9a) {
  d: path("m9 5 3 3 3 -3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.uvgrx_yvv) {
  d: path("M12 3v5");
}

:global(.zt9xgrbcr) {
  d: path("M13.5 11H17a3 3 0 0 1 3 3v3a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3v-3a3 3 0 0 1 3 -3h3.5");
}

</style>
