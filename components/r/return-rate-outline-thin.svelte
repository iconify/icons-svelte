<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="af7iv3n-p"/><path class="iiquwwbvb"/><path class="jnf_2db5t"/><path class="wfnf9nbje"/><path class="jx_6sacnm"/><path class="p4nfdfole"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:return-rate-outline-thin" {...props}></Icon>
<style>
:global(.af7iv3n-p) {
  d: path("M12 2v2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iiquwwbvb) {
  d: path("M5 6.5a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2V16a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

:global(.jnf_2db5t) {
  d: path("M12 18v3");
}

:global(.jx_6sacnm) {
  d: path("m9 14 6 -6");
}

:global(.p4nfdfole) {
  d: path("M13.5 13.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.wfnf9nbje) {
  d: path("M8.5 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
