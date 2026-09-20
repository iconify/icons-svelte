<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k6nj2fbya"/><path class="rkhcgsbdl"/><path class="o759xmblc"/><path class="wew0vnk_n"/><path class="k7cz9qivc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:normalize-data-outline-regular" {...props}></Icon>
<style>
:global(.k6nj2fbya) {
  d: path("M3 5h18");
}

:global(.k7cz9qivc) {
  d: path("M18 11v5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o759xmblc) {
  d: path("M6 8v8");
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.wew0vnk_n) {
  d: path("M12 5v14");
}

</style>
