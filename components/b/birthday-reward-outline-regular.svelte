<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bkd9t9_ww"/><path class="uvgrx_yvv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:birthday-reward-outline-regular" {...props}></Icon>
<style>
:global(.bkd9t9_ww) {
  d: path("M3 21v-7h4V8h10v6h4v7Z");
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

</style>
