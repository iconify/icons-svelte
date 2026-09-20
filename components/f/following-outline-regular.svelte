<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ifsz0izyq"/><path class="j-rdw_bvv"/><path class="t1rg4fbhf"/><path class="pf-zwj5ei"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:following-outline-regular" {...props}></Icon>
<style>
:global(.ifsz0izyq) {
  d: path("M12 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.j-rdw_bvv) {
  d: path("M11 17a4 4 0 0 1 8 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pf-zwj5ei) {
  d: path("m6 10 2 2 -2 2");
}

:global(.t1rg4fbhf) {
  d: path("M3 12h5");
}

</style>
